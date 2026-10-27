<!--
SEO: agent framework radar
-->

<div align="center">

# Agent Framework Radar

Live index of the newest agent frameworks shipping on GitHub, sorted by recency not stars

[![Stars](https://img.shields.io/github/stars/linny006/agent-framework-radar?style=for-the-badge&logo=github)](https://github.com/linny006/agent-framework-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/agent-framework-radar?style=for-the-badge)](https://github.com/linny006/agent-framework-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-15-brightgreen?style=for-the-badge)](#)
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

> ⏰ Last updated: 2026-10-27 13:30 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [autonomous-ai/openharness](https://github.com/autonomous-ai/openharness) | 1375 | TypeScript | 2026-10-27 | The ultimate harness for coding agents and beyond. All your agents. All your machines. One command center. Start with co |
| 2 | [Birfy/agentdescent](https://github.com/Birfy/agentdescent) | 199 | Python | 2026-10-27 | Gradient descent, but the parameters are agents — a parallel, asynchronous framework for self-evolving agents (skills, p |
| 3 | [Team-Commonly/commonly](https://github.com/Team-Commonly/commonly) | 1370 | TypeScript | 2026-10-27 | Open-source room for humans + cross-vendor AI agents. Every agent gets its own name, memory, skills, and workstation. An |
| 4 | [cortexkit/magic-context](https://github.com/cortexkit/magic-context) | 2397 | TypeScript | 2026-10-27 | Unbounded context. Memory that manages itself. One session, for life. The hippocampus for coding agents, part of CortexK |
| 5 | [israriqbal/agent-ecologies](https://github.com/israriqbal/agent-ecologies) | 122 | HTML | 2026-10-27 | Ultimate Multi-Agent OS for Autonomous AI NPCs 2026 |
| 6 | [JdominguezEcommium/agentic-self-regulation-loop](https://github.com/JdominguezEcommium/agentic-self-regulation-loop) | 0 | HTML | 2026-10-27 | 2026 AI Agent Loop v2.0: Autonomous Coding with Guardrails & Self-Healing |
| 7 | [RoadieHQ/openroadie](https://github.com/RoadieHQ/openroadie) | 14 | TypeScript | 2026-10-27 | A live graph of your services, teams, concepts, and dependencies. Highly available, permissioned, and agent-ready. |
| 8 | [Ayobami6/harness](https://github.com/Ayobami6/harness) | 0 | Go | 2026-10-27 | A lightweight, local-first Model Context Protocol (MCP) server, written in Go, that turns your past architectural decisi |
| 9 | [MaxonT/awesome-agent-workflows](https://github.com/MaxonT/awesome-agent-workflows) | 3 | HTML | 2026-10-27 | Curated, star-ranked catalog of AI agent frameworks, coding-agent harnesses and workflow platforms (EN/中文), auto-refresh |
| 10 | [substructureai/subs](https://github.com/substructureai/subs) | 13 | Rust | 2026-10-27 | subs is an agent harness for the cloud. It runs an unprivileged agent loop and uses MCP servers for executing tools. Use |
| 11 | [cmcoffee/gohort](https://github.com/cmcoffee/gohort) | 3 | Go | 2026-10-27 | Your agent has agents. A self-hosted, local-first AI agent platform in one Go binary: agents hand work to specialists an |
| 12 | [Ash20pk/BerthOS](https://github.com/Ash20pk/BerthOS) | 1 | TypeScript | 2026-10-27 | A persistent, kernel-permissioned sandbox for AI agents — real filesystem, browser, and shell, not a bag of stateless AP |
| 13 | [fierceX/mink](https://github.com/fierceX/mink) | 1 | Rust | 2026-10-27 | Lightweight AI coding agent — Rust native, terminal-first, embeddable as a library. Optimized for DeepSeek / OpenAI-comp |
| 14 | [weihuaguo270-ops/react-agent](https://github.com/weihuaguo270-ops/react-agent) | 0 | Python | 2026-10-27 | Agent 业务执行底座：受控工具调用、多应用 HTTP、可审计轨迹与回归闭环 |
| 15 | [dqsjqian/AriaAgent](https://github.com/dqsjqian/AriaAgent) | 6 | C++ | 2026-10-27 | Industrial-grade C++23 Agent Tooling Framework GUI — provider-agnostic LLM agent with true SSE streaming (Continuo trans |
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
