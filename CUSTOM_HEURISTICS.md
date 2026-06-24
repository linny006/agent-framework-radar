# Adding Custom Framework Detection Heuristics

The `agent-framework-radar` uses the GitHub Search API to find new framework repositories by default. If you need more advanced or domain-specific detection heuristics, you can modify the core fetching logic in `tracker.py`.

## 1. Modify the Search Query

The simplest way to tweak the detection heuristic is by changing the `GITHUB_QUERY` constant in `tracker.py`:

```python
# tracker.py
GITHUB_QUERY = 'topic:agent-framework sort:updated-desc'
```

You can update this to search for specific file types, keywords, or different topics.

## 2. Replace the `fetch_items` function

For entirely custom detection heuristics (e.g., querying other APIs, scanning specific organization repos, or applying regex checks on fetched data), you should replace or extend the `fetch_items()` function in `tracker.py`.

The function must return a list of dictionaries containing specific keys to be rendered correctly in the markdown table:

```python
def fetch_items() -> list[dict]:
    # Your custom heuristic logic here
    # Must return a list of dictionaries, each containing:
    # 'id' (str), 'name' (str), 'url' (str), 'stars' (int), 
    # 'language' (str), 'description' (str), 'updated_at' (str)
    pass
```

### Example: Filtering by Custom Logic

If you want to pull from GitHub but filter results based on custom Python logic, you can modify the loop inside `fetch_items`:

```python
def fetch_items() -> list[dict]:
    # ... existing github API request logic ...
    out = []
    for r in resp.json().get("items", [])[:MAX_ITEMS]:
        description = (r.get("description") or "").lower()
        
        # Custom Heuristic: Only include repos with "autonomous" in the description
        if "autonomous" not in description:
            continue
            
        out.append({
            "id": r["full_name"],
            "name": r["full_name"],
            "url": r["html_url"],
            "stars": r["stargazers_count"],
            "language": r.get("language") or "—",
            "description": description[:120],
            "updated_at": r["pushed_at"],
        })
    return out
```

## 3. Test Your Changes

After adding your custom heuristic, run the tracker locally to ensure it fetches the expected data and formats it correctly:

```bash
python tracker.py
```
