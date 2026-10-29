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

> ⏰ Last updated: 2026-10-29 03:15 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [manishiitg/agentworks](https://github.com/manishiitg/agentworks) | 16 | Go | 2026-10-29 | AgentWorks: AI agents that own the work. Goals that chase a metric, and Crews your team asks from Claude, ChatGPT or Cur |
| 2 | [exha1078/agentic-workflow-orchestrator](https://github.com/exha1078/agentic-workflow-orchestrator) | 1 | HTML | 2026-10-29 | 🚀 GenAI Agents Production Blueprint 2026: Code-First Enterprise Deployment |
| 3 | [bbvch-ai/aihub-core](https://github.com/bbvch-ai/aihub-core) | 16 | Python | 2026-10-29 | The open-source AI infrastructure stack for Swiss enterprises. |
| 4 | [fswolf/luna-local-agent](https://github.com/fswolf/luna-local-agent) | 5 | Python | 2026-10-29 | A fully local, private AI voice companion you can see inside: Whisper speech in, Kokoro voice out, memory, tools, plugin |
| 5 | [kh0pper/crow](https://github.com/kh0pper/crow) | 26 | JavaScript | 2026-10-29 | Modular, agentic framework and MCP platform you self-host. Build and run your own AI agents, connect Claude Code, Claude |
| 6 | [pqpo/pragma](https://github.com/pqpo/pragma) | 249 | TypeScript | 2026-10-29 | Build portable agent teams across models and harnesses, with shared memory, skills, tools, and workflows — then bring th |
| 7 | [databricks-solutions/consort](https://github.com/databricks-solutions/consort) | 37 | TypeScript | 2026-10-29 | Consort keeps AI-written code clean and correct: a coordinated ensemble of role agents, spec-first and test-driven, driv |
| 8 | [DemonDamon/AgenticX](https://github.com/DemonDamon/AgenticX) | 769 | Python | 2026-10-29 | AgenticX is a unified, production-ready multi-agent platform — Python SDK + CLI (agx) + Studio server + Machi desktop ap |
| 9 | [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | 20935 | Python | 2026-10-29 | How Python does AI. Agents, realtime voice, image generation, embeddings. Every model, every interface, typed end to end |
| 10 | [footprintjs/agentfootprint](https://github.com/footprintjs/agentfootprint) | 21 | TypeScript | 2026-10-29 | Context engineering, abstracted. Build AI agents whose every LLM call traces back to what was injected, who triggered it |
| 11 | [OLDyade/spark-harness-evolution](https://github.com/OLDyade/spark-harness-evolution) | 0 | TypeScript | 2026-10-29 | An evaluation-driven self-evolution framework for agent harnesses. |
| 12 | [ridemountainpig/open-form](https://github.com/ridemountainpig/open-form) | 7 | TypeScript | 2026-10-29 | A form framework built for agents. |
| 13 | [qbtrix/ripple-iui](https://github.com/qbtrix/ripple-iui) | 8 | TypeScript | 2026-10-29 | 🌊 The Semantic Interface Engine for the Agentic Web. Generative UI from JSON specs, with multistep agent action flows. |
| 14 | [clacky-ai/openclacky](https://github.com/clacky-ai/openclacky) | 1209 | Ruby | 2026-10-29 | The most Token-efficient open-source AI Agent |
| 15 | [erishen/resolve-studio](https://github.com/erishen/resolve-studio) | 0 | TypeScript | 2026-10-29 | Agent harness monorepo: a Cordis-powered plugin runtime hosting a PSE (Planner-Specialist-Evaluator) multi-agent system  |
| 16 | [yangheng95/opencorvus](https://github.com/yangheng95/opencorvus) | 308 | TypeScript | 2026-10-29 | DIY your own agent team harness for long-horizon agent work |
| 17 | [ourostack/ouroboros](https://github.com/ourostack/ouroboros) | 3 | TypeScript | 2026-10-29 | TypeScript harness for building personal AI agents with durable memory — agents that live across your channels (CLI, Tea |
| 18 | [ShiftAboveCtrl/ai17z](https://github.com/ShiftAboveCtrl/ai17z) | 7 | TypeScript | 2026-10-29 | Local-first platform for persistent autonomous AI agents. Identity, memory, relationships, beliefs, knowledge and policy |
| 19 | [shibing624/agentica](https://github.com/shibing624/agentica) | 359 | Python | 2026-10-29 | One person, a team of agents: CLI, Web, Desktop & Python SDK with multi-session collaboration, persistent memory, and se |
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
