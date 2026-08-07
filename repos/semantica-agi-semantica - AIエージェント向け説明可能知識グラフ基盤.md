---
url: https://github.com/semantica-agi/semantica
saved: 2026-08-07
tags:
  - python
  - trending
  - agent-memory
  - ai
  - ai-governance
  - ai-infrastructure
  - artificial-intelligence
  - context-engineering
  - context-graphs
  - data-engineering
  - decision-intelligence
  - developer-tools
  - explainable-ai
  - generative-ai
  - graph-rag
  - knowledge-graph
  - llm
  - ontology
  - provenance
  - reasoning
  - semantic-search
category: GitHub Trending
status: 未読
rating:
---

# semantica-agi/semantica

▎ AIエージェント向け説明可能知識グラフ基盤

ライセンス: MIT
言語: Python
スター数: ⭐ 2300 (+118 今日)
トレンド順位: #7 (2026-08-07)

---
## 概要

Semanticaは「AIエージェント版オープンソースPalantir」を掲げる、グラフネイティブなコンテキスト・意思決定基盤です。企業データを取り込み、エンティティや関係を抽出してコンテキストグラフ・ナレッジグラフを構築し、その上でグラフ分析や因果推論を、決定の由来(プロベナンス)を完全に保持したまま実行できます。LLMやベクトルストア、既存のエージェントフレームワークを置き換えるのではなく、その下層に決定論的なインフラ層として組み込む設計であり、グラフ構築や推論にLLMを必要としない点が特徴です。金融・医療・法務・政府などの規制産業でAIエージェントの意思決定を「なぜそう判断したか」を後から説明可能にしたいAI/MLプラットフォームチーム、コンプライアンス・監査担当者、Databricks/Snowflakeなどのデータ基盤チームを主な対象としています。ベンダーロックインのないセルフホスト型で、W3C PROV-Oなどの標準規格に準拠している点も特徴です。

---
## 主な機能・特徴

- コンテキストグラフ — エージェントが知り、判断し、推論するすべてを構造化されたグラフとして保持
- 意思決定インテリジェンス — 決定を一級オブジェクト化し、追跡・類似判断の検索・因果関係の紐付けが可能
- 完全な監査証跡 — W3C PROV-Oに基づく由来情報をJSON/CSV/RDFでエクスポート
- 決定論的推論エンジン — 前向き連鎖・Reteネットワーク・Datalog・SPARQLによる説明可能な推論
- エンタープライズ連携 — Databricks(Unity Catalog)やSnowflakeとのネイティブ連携でデータ移行なしにグラフ化
- 多様なグラフストレージ対応 — RDF(Oxigraph、Blazegraph等)とLPG(Neo4j、Neptune等)をコード変更なしで切替可能
- ガバナンス機能 — SHACL制約、矛盾検出、OWL/SKOSによるオントロジー管理

---
## トレンド入り理由の推測

Semanticaは本日118スターを獲得しており、総スター数2,300程度に対する急激な伸びは見られないものの、着実に注目を集めています。背景には「LLMエージェントの判断がブラックボックス化する」という現在のAI業界全体の課題があり、金融・医療など規制産業でAIを導入する際の説明責任(Explainability)や監査対応へのニーズが急速に高まっていることが挙げられます。ベクトルDBとRAGだけでは決定履歴やプロベナンスを保持できないという弱点を明確に補完するポジショニングが、エンタープライズ寄りの開発者やコンプライアンス担当者に刺さっていると考えられます。

また、Databricks/Snowflakeなど既存のデータレイクハウス基盤とネイティブ連携できる点は、企業の既存インフラを活かしたいデータプラットフォームチームにとって導入障壁が低く、PyPI配布やDeepWikiドキュメント、Discordコミュニティなど周辺エコシステムも整備されていることから、実務での採用検討が進みやすい状況にあると推測されます。

---
## 関連リンク

- https://github.com/semantica-agi/semantica
- https://getsemantica.ai/

---
## メモ

