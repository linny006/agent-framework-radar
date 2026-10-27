<!--
SEO: agent framework radar
-->

<div align="center">

# Agent Framework Radar

Live index of the newest agent frameworks shipping on GitHub, sorted by recency not stars

[![Stars](https://img.shields.io/github/stars/linny006/agent-framework-radar?style=for-the-badge&logo=github)](https://github.com/linny006/agent-framework-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/agent-framework-radar?style=for-the-badge)](https://github.com/linny006/agent-framework-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-14-brightgreen?style=for-the-badge)](#)
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

> ⏰ Last updated: 2026-10-27 20:00 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [siso-os/siso-whatsapp-link](https://github.com/siso-os/siso-whatsapp-link) | 0 | Go | 2026-10-27 | Scan a QR code and your agents can read and answer WhatsApp. |
| 2 | [Birfy/agentdescent](https://github.com/Birfy/agentdescent) | 199 | Python | 2026-10-27 | Gradient descent, but the parameters are agents — a parallel, asynchronous framework for self-evolving agents (skills, p |
| 3 | [israriqbal/agent-ecologies](https://github.com/israriqbal/agent-ecologies) | 121 | HTML | 2026-10-27 | Ultimate Multi-Agent OS for Autonomous AI NPCs 2026 |
| 4 | [ybak/ai-tutorial](https://github.com/ybak/ai-tutorial) | 15 | JavaScript | 2026-10-27 |  一本开源的 AgentScope Java 中文教程：7 篇 44 章、839 页成书体量的完整 Markdown 源稿，由浅入深覆盖从第一个 Agent 到生产级 Agent 平台的全部主题。 |
| 5 | [RoadieHQ/openroadie](https://github.com/RoadieHQ/openroadie) | 14 | TypeScript | 2026-10-27 | A live graph of your services, teams, concepts, and dependencies. Highly available, permissioned, and agent-ready. |
| 6 | [fierceX/mink](https://github.com/fierceX/mink) | 1 | Rust | 2026-10-27 | Lightweight AI coding agent — Rust native, terminal-first, embeddable as a library. Optimized for DeepSeek / OpenAI-comp |
| 7 | [dqsjqian/AriaAgent](https://github.com/dqsjqian/AriaAgent) | 6 | C++ | 2026-10-27 | Industrial-grade C++23 Agent Tooling Framework GUI — provider-agnostic LLM agent with true SSE streaming (Continuo trans |
| 8 | [open1s/bos](https://github.com/open1s/bos) | 1 | Rust | 2026-10-27 | AI agent framework with multi-language bindings. Agents, tools, bus, MCP, skills — in Rust, Python & JavaScript. |
| 9 | [Search2o/agent-server](https://github.com/Search2o/agent-server) | 0 | Python | 2026-10-27 | Build, run, and use hundreds of AI microagents through search |
| 10 | [AgentsKit-io/agentskit-registry](https://github.com/AgentsKit-io/agentskit-registry) | 6 | TypeScript | 2026-10-27 | Ready-to-use AI agents for AgentsKit — shadcn-style: copy the source into your project. registry.agentskit.io |
| 11 | [ivaNov-0042/opencode-multiagents-project-templates](https://github.com/ivaNov-0042/opencode-multiagents-project-templates) | 0 | Python | 2026-10-26 | Multi-agent research workspace template for opencode v2 — identity claiming, shared task board, JSON-truth memory, CLI-n |
| 12 | [aloth/overleaf-skill](https://github.com/aloth/overleaf-skill) | 23 | Shell | 2026-10-26 | Agent Skill for Overleaf — Automate LaTeX project management, sync, and compilation for AI assistants |
| 13 | [numbpill3d/switchboard](https://github.com/numbpill3d/switchboard) | 1 | JavaScript | 2026-10-26 |  ai-agent multiplexer with a minimal  ui...claude, opencode, codex and more in tabs, each with a live typing/thinking/wa |
| 14 | [tinyhumansai/tinycortex](https://github.com/tinyhumansai/tinycortex) | 264 | Rust | 2026-10-26 | The Fastest AI Memory Model - Your Second Brain |
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
