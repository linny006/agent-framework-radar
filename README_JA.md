# agent-framework-radar

> GitHub に登場した最新の Agent フレームワークをリアルタイムでインデックス化。スター数ではなく公開日順で並べてます

[English](./README.md) · [中文](./README_CN.md) · **日本語** · [한국어](./README_KO.md) · [Español](./README_ES.md) · [Português](./README_PT.md)

[![Stars](https://img.shields.io/github/stars/linny006/agent-framework-radar?style=for-the-badge&logo=github)](https://github.com/linny006/agent-framework-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/agent-framework-radar?style=for-the-badge)](https://github.com/linny006/agent-framework-radar/commits)

---

GitHub 上の新しい Agent フレームワークリポジトリを継続的に発見・インデックス化する軽量トラッカーです。スター数の多い定番プロジェクトに偏りがちなキュレーションリストとは違い、このツールはフレームワークが公開されたその日に拾い上げ、開発者が新興の選択肢をいち早く把握できるようにします。

このリストは GitHub Actions の cron によって**15 分ごとに自動更新**されます。各コミットは上流データソースの実際の変化を反映しています——新規アイテムの追加、期限切れアイテムの削除——なので、表示されている内容は常に最新です。

---

15 分ごとに GitHub Action が `tracker.py` を実行します。このスクリプトは以下を行います：

1. `GitHub Search API` から最新の状態を取得する。
2. `data/items.json`（前回のスナップショット）と差分を取る。
3. `<!-- TRACKER_TABLE_* -->` マーカー間のテーブルを書き換える。
4. 変更があれば `feat: +N added, -M removed (timestamp)` をコミットする。

外部サービスなし。有料 API なし。公開データソースと無料の GitHub Action だけで動いています。

---

## 📋 Live data

ライブデータは英語版 README をご覧ください

---

## 🔗 Related live trackers

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
