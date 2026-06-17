---
url: https://github.com/DeusData/codebase-memory-mcp
saved: 2026-06-17
tags:
  - c
  - trending
  - tree-sitter
  - sqlite
  - mcp
  - opencode
  - code-analysis
  - ast
  - knowledge-graph
  - developer-tools
  - cursor
  - graph-visualization
  - cypher
  - codex
  - windsurf
  - code-intelligence
  - aider
  - gemini-cli
  - model-context-protocol
  - mcp-server
  - claude-code
  - kilocode
category: GitHub Trending
status: 未読
rating:
---

# DeusData/codebase-memory-mcp

▎ 高性能コード知識グラフMCPサーバー

ライセンス: MIT
言語: C
スター数: ⭐ 5000 (+718 今日)
トレンド順位: #1 (2026-06-17)

---
## 概要

codebase-memory-mcpは、コードベースを永続的な知識グラフにインデックス化する高性能MCPサーバーである。LLMを内蔵せず、tree-sitterによるAST解析を用いて158言語に対応し、9つの主要言語ではセマンティック型解決も提供する。Linuxカーネル規模のリポジトリでも約3分でインデックス化が完了し、サブミリ秒のクエリ応答を実現する。従来のファイル単位探索と比較してトークン消費を99.2%削減できるため、AIコーディングエージェントとの連携において圧倒的なコスト効率を発揮する。単一の静的バイナリとして配布され、ランタイム依存ゼロでmacOS・Linux・Windowsに対応。Claude Code、Cursor、Codexなど11種のコーディングエージェントを自動設定でサポートし、3Dグラフ可視化機能も搭載している。

---
## 主な機能・特徴

- 超高速インデックス — tree-sitter AST解析により平均リポジトリをミリ秒単位で処理
- 158言語対応 — 広範なプログラミング言語のコード解析をサポート
- 99.2%トークン削減 — ファイル単位探索に比べ圧倒的に少ないトークンで情報取得
- 知識グラフ構築 — コードの構造的関係をグラフとしてSQLiteに永続化
- 11種AIエージェント対応 — Claude Code、Cursor、Codex、Aiderなどを自動設定
- 3Dグラフ可視化 — コードベースの依存関係を視覚的に探索可能
- インフラコード対応 — Dockerfile、Kubernetesマニフェストもインデックス化
- クロスサービスリンク — HTTP、gRPC、GraphQL、tRPCプロトコルを横断的に追跡

---
## トレンド入り理由の推測

本日1日で718スターという急激なスター増加は、AIコーディングエージェントの普及が加速する中で、コンテキスト管理の課題に対する決定的なソリューションとして注目を集めていることを示している。Claude Code、Cursor、Codexなど主要なAIコーディングツールがすべてMCP対応を進めており、それらのエージェントに「コードベース全体の理解」を効率的に提供できるツールへの需要が急増している。

特に99.2%のトークン削減という性能指標は、LLMの利用コストが企業にとって大きな課題となっている現在、開発者コミュニティに強いインパクトを与えている。C言語による実装で単一バイナリ・ゼロ依存という設計思想も、パフォーマンスを重視する開発者層に響いている。

さらに、MCP（Model Context Protocol）エコシステムの成熟に伴い、「知識グラフ」アプローチによるコード理解がファイル単位の従来手法を置き換える次世代パラダイムとして認知されつつある。pushed_atが最近であることから、新機能リリースや主要アップデートがトレンド入りの直接的なトリガーとなった可能性が高い。

---
## 関連リンク

- https://github.com/DeusData/codebase-memory-mcp
- https://deusdata.github.io/codebase-memory-mcp/

---
## メモ
