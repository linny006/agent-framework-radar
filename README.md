<!--
SEO: agent framework radar
-->

<div align="center">

# Agent Framework Radar

Live index of the newest agent frameworks shipping on GitHub, sorted by recency not stars

[![Stars](https://img.shields.io/github/stars/linny006/agent-framework-radar?style=for-the-badge&logo=github)](https://github.com/linny006/agent-framework-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/agent-framework-radar?style=for-the-badge)](https://github.com/linny006/agent-framework-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-18-brightgreen?style=for-the-badge)](#)
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

> ⏰ Last updated: 2026-10-27 12:00 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [fabbrik/AgentExperience.NET](https://github.com/fabbrik/AgentExperience.NET) | 3 | C# | 2026-10-27 | Portable, evidence-backed experience memory for .NET AI agents built on Microsoft Agent Framework |
| 2 | [lioensky/VCPToolBox](https://github.com/lioensky/VCPToolBox) | 2406 | JavaScript | 2026-10-27 | VCP 部署在 AI 模型 API 与前端应用之间，是面向AGI OS开发和探索的工业级基建示范项目。通过统一指令协议、多层级持久化记忆、分布式插件引擎及多 Agent 协作框架，将原本“无状态、无记忆、无工具调用能力”的大语言模型，彻底改 |
| 3 | [pqpo/pragma](https://github.com/pqpo/pragma) | 249 | TypeScript | 2026-10-27 | Build portable agent teams across models and harnesses, with shared memory, skills, tools, and workflows — then bring th |
| 4 | [wszx11/agent-control-fabric](https://github.com/wszx11/agent-control-fabric) | 0 | Python | 2026-10-27 | Focus-safe, window-routed execution fabric for multi-agent computer control. |
| 5 | [Anmulzhao/DSH-AGINT](https://github.com/Anmulzhao/DSH-AGINT) | 1 | JavaScript | 2026-10-27 | Self-evolving agent framework on DeepSeek Harness (dsh): 40 Cordis plugins, 4 presets, memory · reflection · gates · met |
| 6 | [swsgbl/hmharness](https://github.com/swsgbl/hmharness) | 5 | TypeScript | 2026-10-27 | 为鸿蒙 (HarmonyOS/OpenHarmony) 开发全流程而生的自进化智能体框架——零依赖内核、自进化一等公民、MCP 生态借力、模拟器与工具链无头全控。Self-evolving agent framework for the f |
| 7 | [diego-sicignano/soundpitch](https://github.com/diego-sicignano/soundpitch) | 0 | Python | 2026-10-27 | Audio-first football match companion for blind and low-vision fans: verified audio description from synthetic match even |
| 8 | [yangheng95/opencorvus](https://github.com/yangheng95/opencorvus) | 308 | TypeScript | 2026-10-27 | DIY your own agent team harness for long-horizon agent work |
| 9 | [ZJU-REAL/HugAgentOS](https://github.com/ZJU-REAL/HugAgentOS) | 624 | Python | 2026-10-27 | HugAgentOS: the open-source Agent Harness that runs 24/7 |
| 10 | [shadow3aaa/DaatLocus](https://github.com/shadow3aaa/DaatLocus) | 8 | Rust | 2026-10-27 | An agent runtime. |
| 11 | [Prescott-Data/jarviscore-agents](https://github.com/Prescott-Data/jarviscore-agents) | 1 | Python | 2026-10-27 | Complete agent systems built on JarvisCore, open-sourced as blueprints: multiplayer, GTM, software reliability and perso |
| 12 | [Nucc/spoletta](https://github.com/Nucc/spoletta) | 0 | Go | 2026-10-27 | Visual builder and engine for agent workflows |
| 13 | [zzjha-cn/agent_sandbox](https://github.com/zzjha-cn/agent_sandbox) | 0 | Go | 2026-10-27 | Managing a Docker environment as a sandbox for running agent-cli (like claude or codex) |
| 14 | [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) | 35979 | Go | 2026-10-27 | A reliable coding agent for complex software engineering tasks. |
| 15 | [Lykhoyda/QaReN](https://github.com/Lykhoyda/QaReN) | 20 | TypeScript | 2026-10-27 | Claude Code \| Codex plugin for React Native — explores codebases, designs architecture, implements features and QA the c |
| 16 | [shibing624/agentica](https://github.com/shibing624/agentica) | 358 | Python | 2026-10-27 | One person, a team of agents: CLI, Web, Desktop & Python SDK with multi-session collaboration, persistent memory, and se |
| 17 | [bbvch-ai/aihub-core](https://github.com/bbvch-ai/aihub-core) | 16 | Python | 2026-10-27 | The open-source AI infrastructure stack for Swiss enterprises. |
| 18 | [ljchang/mecha](https://github.com/ljchang/mecha) | 7 | Rust | 2026-10-27 | A standalone agent harness in Rust: a provider-agnostic loop, MCP tools, a path jail and prompt-injection interlock, san |
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
