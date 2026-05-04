---
url: https://github.com/cocoindex-io/cocoindex
saved: 2026-05-04
tags:
  - python
  - trending
  - agentic-data-framework
  - ai
  - ai-agents
  - change-data-capture
  - codebase-intelligence
  - context-engineering
  - data-engineering
  - data-indexing
  - data-processing
  - etl
  - indexing
  - knowledge-graph
  - llm
  - long-horizon-agent
  - rag
  - real-time
  - rust
  - semantic-search
category: GitHub Trending
status: 未読
rating:
---

# cocoindex-io/cocoindex

▎ 長期エージェント向け増分インデックスエンジン

ライセンス: Apache-2.0
言語: Python
スター数: ⭐ 7921 (+204 今日)
トレンド順位: #14 (2026-05-04)

---
## 概要

CocoIndexは、長期エージェント（Long Horizon Agent）向けに設計された増分データ処理エンジンです。コードベース・会議メモ・メール・Slack・PDF・動画などを継続的にフレッシュなコンテキストに変換し、AIエージェントやLLMアプリケーションが常に最新の情報で推論できる環境を提供します。従来のバッチ処理でデータが陳腐化する問題を解決するため、変更があった差分（Δ）のみを再処理する増分処理アーキテクチャを採用しています。PythonのフロントエンドとRustのコアエンジンを組み合わせ、宣言的なAPIで5分以内にRAGパイプラインを構築できます。ベクトル検索・知識グラフ・セマンティック検索などに対応し、PostgreSQLをはじめとする各種ストレージと連携します。Apache 2.0ライセンスで公開されており、20以上の実用サンプルも提供されています。

---
## 主な機能・特徴

- 増分処理 — 変更差分のみを再処理しバッチ処理より大幅に高効率
- 宣言的Python API — pip install cocoindex だけで5分以内にセットアップ可能
- Rustコアエンジン — 高速・安定した並列処理基盤
- マルチソース対応 — コードベース・PDF・Slack・会議メモ等多様なデータソース
- ベクトル検索/RAG — LLMアプリ向けのセマンティック検索インフラを簡単構築
- MCP連携 — Claude CodeやCursorとのMCPサーバー統合をサポート
- 知識グラフ構築 — コードのAST解析・コールグラフ生成等の高度な索引化

---
## トレンド入り理由の推測

cocoindex-io/cocoindexが2026年5月4日に204スターを獲得してトレンド入りした背景には、AIエージェントの「コンテキスト鮮度」問題への注目が集まっていることがあります。LLMを使ったプロダクションアプリケーションでは、データが頻繁に更新される中でRAGパイプラインが古い情報を参照してしまう問題が深刻化しており、CocoIndexはこの課題に直接答えるソリューションを提供しています。

pushed_atが2026-05-04（当日）であり、最新のアップデートが反映された直後に注目が集まったと推測されます。コードベースインテリジェンス向けのフラグシップMCPサーバー「CocoIndex-code」がClaude CodeやCursorとの統合をサポートしており、これらのツールユーザーへのアピールが特にエンジニアコミュニティでの拡散を後押ししています。

PythonフロントエンドとRustコアエンジンという組み合わせは、開発の利便性と実行時パフォーマンスを両立した選択として技術者から高く評価されています。日本語を含む9言語のREADME翻訳が提供されており、グローバルなコミュニティへのリーチも広がっています。

---
## 関連リンク

- https://github.com/cocoindex-io/cocoindex
- https://cocoindex.io

---
## メモ

