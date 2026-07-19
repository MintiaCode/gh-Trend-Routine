---
url: https://github.com/Canner/WrenAI
saved: 2026-07-19
tags:
  - python
  - trending
  - agent
  - bigquery
  - charts
  - sql
  - postgresql
  - openai
  - vertex
  - genbi
  - text-to-sql
  - rag
  - text2sql
  - duckdb
  - llm
  - anthropic
  - sqlai
  - text-to-chart
  - context-engineering
category: GitHub Trending
status: 未読
rating:
---

# Canner/WrenAI

▎ AIエージェント向けガバナンス型text-to-SQL基盤

ライセンス: Apache-2.0
言語: Python
スター数: ⭐ 16100 (+96 今日)
トレンド順位: #17 (2026-07-19)

---
## 概要

WrenAIは、AIエージェントが信頼できるビジネスインテリジェンス(BI)を生成するための課題を解決するオープンソースの「GenBI(Generative BI)」基盤です。従来のtext-to-SQLアプローチは不正確なSQLを生成しがちで、またビジネス上の文脈がベンダー独自のインターフェースに閉じ込められがちという問題がありました。WrenAIは、レビュー可能でバージョン管理されたコンテキスト層を通じて、自然言語の質問を信頼できるダッシュボード・チャート・SQLに変換する「オープンコンテキストレイヤー」を提供することでこれを解決します。中核にはRust製のApache DataFusionを用いたセマンティックエンジンがあり、Modeling Definition Language(MDL)でビジネスロジックを表現し、BigQuery・Snowflake・PostgreSQLなど20以上のデータソースに対応します。ブラウザ側で動くWebAssembly版エンジンによりVercelやCloudflare Pagesへのダッシュボード配信も可能です。データウェアハウスを持つ組織で、AIエージェントに説明責任のあるBI成果物を作らせたい開発者やデータチームを主な対象としています。

---
## 主な機能・特徴

- セマンティックエンジン — Apache DataFusion(Rust)ベースで20以上のデータソースに対応
- Modeling Definition Language(MDL) — ビジネスロジックをGitフレンドリーな形式で定義
- コンテキストレイヤー — LanceDBによるハイブリッド検索でスキーマと非構造化文書を統合
- ガバナンス機能 — 行・列レベルのアクセス制御とdry-plan検証
- ブラウザ実行可能なダッシュボード — wren-core-wasmによりVercel/Cloudflare Pagesへデプロイ
- LangChain/LangGraph連携 — エージェントオーケストレーションを前提としたPythonバインディング
- 3段階ワークフロー — SQL生成→ダッシュボード配信→ナレッジのレビュー・維持を一気通貫で提供

---
## トレンド入り理由の推測

2026年5月にWren Engineがメインリポジトリの`/core/`へ統合され、旧来のDocker中心・チャット中心の製品は「Wren GenBI Classic」としてレガシー化されるという大きなアーキテクチャ転換が行われました。直近の2026年7月13日にはv0.13.0がリリースされており、この統合後の新方向性が固まりつつあるタイミングでの注目集めがトレンド入りの一因と考えられます。

text-to-SQL・BIの自動化はLLMエージェントの実用化が進む中で企業ニーズが強い領域であり、特に「AIエージェントにSQLを書かせるが、結果は人がガバナンスできる状態を保ちたい」という要求は今のAI導入企業に共通する課題です。Anthropic(Claude)やOpenAIなど複数のLLMプロバイダーに対応し、RAGやcontext-engineeringといった最新トピックを前面に押し出している点も、AIエージェント文脈での関心を引きやすい要因と推測されます。

---
## 関連リンク

- https://github.com/Canner/WrenAI
- https://getwren.ai

---
## メモ
