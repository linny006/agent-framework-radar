<!--
SEO: agent framework radar
-->

<div align="center">

# Agent Framework Radar

Live index of the newest agent frameworks shipping on GitHub, sorted by recency not stars

[![Stars](https://img.shields.io/github/stars/linny006/agent-framework-radar?style=for-the-badge&logo=github)](https://github.com/linny006/agent-framework-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/agent-framework-radar?style=for-the-badge)](https://github.com/linny006/agent-framework-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-19-brightgreen?style=for-the-badge)](#)
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

> ⏰ Last updated: 2026-10-27 12:15 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [manishiitg/agentworks](https://github.com/manishiitg/agentworks) | 16 | Go | 2026-10-27 | AgentWorks: AI agents that own the work. Goals that chase a metric, and Crews your team asks from Claude, ChatGPT or Cur |
| 2 | [autonomous-ai/openharness](https://github.com/autonomous-ai/openharness) | 1375 | TypeScript | 2026-10-27 | The ultimate harness for coding agents and beyond. All your agents. All your machines. One command center. Start with co |
| 3 | [SourceShift/mini-ork](https://github.com/SourceShift/mini-ork) | 32 | Python | 2026-10-27 | Prove an AI-written fix actually fixes the bug. mini-ork certify reproduces the bug against your repo's own code, attack |
| 4 | [cortexkit/aft](https://github.com/cortexkit/aft) | 333 | Rust | 2026-10-27 | Give your agent a proper IDE and OS. The sensorimotor cortex for coding agents (OpenCode + Pi), part of CortexKit: symbo |
| 5 | [pqpo/pragma](https://github.com/pqpo/pragma) | 249 | TypeScript | 2026-10-27 | Build portable agent teams across models and harnesses, with shared memory, skills, tools, and workflows — then bring th |
| 6 | [axisvela/praxo-core](https://github.com/axisvela/praxo-core) | 12 | Go | 2026-10-27 | MIT-licensed agent framework for the AxisVela ecosystem: governed agent loop, model/tool/memory/event primitives, plugin |
| 7 | [cortexkit/magic-context](https://github.com/cortexkit/magic-context) | 2398 | TypeScript | 2026-10-27 | Unbounded context. Memory that manages itself. One session, for life. The hippocampus for coding agents, part of CortexK |
| 8 | [Anmulzhao/DSH-AGINT](https://github.com/Anmulzhao/DSH-AGINT) | 1 | JavaScript | 2026-10-27 | Self-evolving agent framework on DeepSeek Harness (dsh): 40 Cordis plugins, 4 presets, memory · reflection · gates · met |
| 9 | [ozgurulukir/rubik](https://github.com/ozgurulukir/rubik) | 0 | Ruby | 2026-10-27 | Ruby agent harness with fail-closed security gates (command gate, sandbox), a revertible-effect composable runtime, MCP  |
| 10 | [microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit) | 6479 | Python | 2026-10-27 | AI Agent Governance Toolkit — Policy enforcement, zero-trust identity, execution sandboxing, and reliability engineering |
| 11 | [JdominguezEcommium/agentic-self-regulation-loop](https://github.com/JdominguezEcommium/agentic-self-regulation-loop) | 0 | HTML | 2026-10-27 | 2026 AI Agent Loop v2.0: Autonomous Coding with Guardrails & Self-Healing |
| 12 | [daretodave/nexus](https://github.com/daretodave/nexus) | 5 | JavaScript | 2026-10-27 | a methodology for autonomous projects that ship themselves (hands off) |
| 13 | [bigduu/Bamboo-agent](https://github.com/bigduu/Bamboo-agent) | 21 | Rust | 2026-10-27 | Bamboo — a local-first Rust agent harness and runtime with sessions, tools, skills, MCP, sub-agents, workflows, schedule |
| 14 | [shibing624/agentica](https://github.com/shibing624/agentica) | 358 | Python | 2026-10-27 | One person, a team of agents: CLI, Web, Desktop & Python SDK with multi-session collaboration, persistent memory, and se |
| 15 | [bbvch-ai/aihub-core](https://github.com/bbvch-ai/aihub-core) | 16 | Python | 2026-10-27 | The open-source AI infrastructure stack for Swiss enterprises. |
| 16 | [whyihaveyou/dsh-suite](https://github.com/whyihaveyou/dsh-suite) | 64 | HTML | 2026-10-27 | The living DeepSeek Harness plugin directory — refreshed hourly, compat-tested daily, with an in-app plugin store and sc |
| 17 | [colmugx/posoco-extension](https://github.com/colmugx/posoco-extension) | 2 | MoonBit | 2026-10-27 | Official extension collection for posoco |
| 18 | [Gi-Tuu/yai-agent-core](https://github.com/Gi-Tuu/yai-agent-core) | 9 | Python | 2026-10-27 | Embeddable self-adaptive agent kernel for host applications |
| 19 | [joelaniol/nova](https://github.com/joelaniol/nova) | 1 | — | 2026-10-27 | Nova AI Workspace — the local browser workspace where your AI agents work. Real logged-in sessions, terminal, memory, sc |
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
