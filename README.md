<!--
SEO: agent framework radar
-->

<div align="center">

# Agent Framework Radar

Live index of the newest agent frameworks shipping on GitHub, sorted by recency not stars

[![Stars](https://img.shields.io/github/stars/linny006/agent-framework-radar?style=for-the-badge&logo=github)](https://github.com/linny006/agent-framework-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/agent-framework-radar?style=for-the-badge)](https://github.com/linny006/agent-framework-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-10-brightgreen?style=for-the-badge)](#)
[![Updated](https://img.shields.io/badge/Updates-every_15min-blue?style=for-the-badge)](#)

**⭐ Star this repo to bookmark — fresh data every 15 minutes**

[English](./README.md) · [中文](./README_CN.md) · [日本語](./README_JA.md) · [한국어](./README_KO.md) · [Español](./README_ES.md) · [Português](./README_PT.md)

</div>

---

## 💡 What is this?

A lightweight tracker that continuously discovers and indexes new agent framework repositories on GitHub. Unlike curated awesome-lists that favor established projects with high star counts, this tool surfaces frameworks the day they ship, giving developers early visibility into emerging options.

This list is **auto-updated every 15 minutes** by a GitHub Actions cron.
Each commit reflects a real change in the upstream data source — new items added,
expired items removed — so you can rely on what you see being current.

---

## 📋 Current Items

> ⏰ Last updated: 2026-10-27 12:45 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [kindgi/kindgi-sdk](https://github.com/kindgi/kindgi-sdk) | 3 | TypeScript | 2026-10-27 | Kindgi SDK — public Apache-2.0 packages for building on Kindgi (preview) |
| 2 | [axisvela/praxo-core](https://github.com/axisvela/praxo-core) | 12 | Go | 2026-10-27 | MIT-licensed agent framework for the AxisVela ecosystem: governed agent loop, model/tool/memory/event primitives, plugin |
| 3 | [HKUDS/nanobot](https://github.com/HKUDS/nanobot) | 49474 | Python | 2026-10-27 | Ultra-lightweight, open-source, self-hosted personal AI agent framework in Python with WebUI, tools, memory, MCP, multi- |
| 4 | [beesyst/beeagent](https://github.com/beesyst/beeagent) | 2 | Python | 2026-10-27 | Modular AI agent runtime for explainable, stateful, and bounded workflows with explicit module, capability, and executio |
| 5 | [linny006/agent-framework-radar](https://github.com/linny006/agent-framework-radar) | 9 | Python | 2026-10-27 | Live index of the newest agent frameworks shipping on GitHub, sorted by recency not stars |
| 6 | [dshakes/lantern](https://github.com/dshakes/lantern) | 1 | TypeScript | 2026-10-27 | Production runtime for AI agents — run the whole stack locally with one command, ship to your own cloud. Real WhatsApp/S |
| 7 | [arcships/rutis](https://github.com/arcships/rutis) | 160 | Rust | 2026-10-27 | A plugin runtime for software that iterates on itself — the substrate where agents write, swap and hot-reload their own  |
| 8 | [cortexkit/aft](https://github.com/cortexkit/aft) | 333 | Rust | 2026-10-27 | Give your agent a proper IDE and OS. The sensorimotor cortex for coding agents (OpenCode + Pi), part of CortexKit: symbo |
| 9 | [aisecnomad/Nexus-ShadowScan](https://github.com/aisecnomad/Nexus-ShadowScan) | 16 | Python | 2026-10-27 | ShadowScan discovers AI usage and agent evidence across code, runtime, network, endpoints, identity, gateways, low-code, |
| 10 | [hara-cli/hara](https://github.com/hara-cli/hara) | 3 | TypeScript | 2026-10-27 | A coding agent CLI that runs like an engineering org — role routing, plan DAGs, approvals, memory, and a 10-platform cha |
<!-- TRACKER_TABLE_END -->

---

## 🔍 How it works

Every 15 minutes, a GitHub Action runs `tracker.py`. That script:

1. Fetches the latest state from `GitHub Search API`.
2. Diffs against `data/items.json` (the previous snapshot).
3. Rewrites the table above between the `<!-- TRACKER_TABLE_* -->` markers.
4. Commits `feat: +N added, -M removed (timestamp)` if anything changed.

No external services. No paid APIs. Just a public data source and a free GitHub Action.

---

## 🤝 Contributing

See `CONTRIBUTING.md` — usually you don't need to: the tracker keeps itself current.
If you spot a data-source bug or want to suggest a new column for the table, open
an issue.

---

## 🔗 Related live trackers

If you find this useful, you might also like these other auto-updated
trackers from the same maintainer — same mechanism, different upstream:

- [trending-claude-skills](https://github.com/linny006/trending-claude-skills) — What's shipping in Claude Skills this week (`topic:claude-skills`)
- [mcp-servers-live](https://github.com/linny006/mcp-servers-live) — Live index of newest MCP servers (`topic:mcp-server`)
- [cursor-rules-live](https://github.com/linny006/cursor-rules-live) — Newest Cursor rules and .cursorrules patterns (`topic:cursor-rules`)
- [claude-code-plugin-tracker](https://github.com/linny006/claude-code-plugin-tracker) — Claude Code plugins and hook configs (`topic:claude-code`)
- [llm-agents-radar](https://github.com/linny006/llm-agents-radar) — Newest LLM agent frameworks (`topic:llm-agent`)
- [rag-radar](https://github.com/linny006/rag-radar) — Newest RAG implementations and tools (`topic:rag`)
- [llm-eval-tracker](https://github.com/linny006/llm-eval-tracker) — Newest LLM evaluation tools and benchmarks (`topic:llm-eval`)
- [vector-db-live](https://github.com/linny006/vector-db-live) — Newest vector DB projects and integrations (`topic:vector-database`)
- [llmops-radar](https://github.com/linny006/llmops-radar) — Newest LLMOps tooling (observability, deployment) (`topic:llmops`)
- [prompt-tools-live](https://github.com/linny006/prompt-tools-live) — Newest prompt-engineering tools and prompt repos (`topic:prompt-engineering`)
- [agent-eval-harness](https://github.com/linny006/agent-eval-harness) — Live benchmark of AI coding agents (`topic:llm-eval`)
- [skills-tracker](https://github.com/linny006/skills-tracker) — Tracking new GitHub 'skills' repos (`topic:agent-skills`)
- [awesome-agent-skills](https://github.com/linny006/awesome-agent-skills) — Curated auto-updated awesome-list of AI agent skills (`topic:agent-skills`)

---

## 📜 License

MIT — see `LICENSE`.
