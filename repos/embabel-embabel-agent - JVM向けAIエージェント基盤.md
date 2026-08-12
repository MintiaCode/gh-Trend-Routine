---
url: https://github.com/embabel/embabel-agent
saved: 2026-08-12
tags:
  - kotlin
  - trending
  - agent
  - agentic-ai
  - agents
  - ai
  - ai-agents
  - aiagentframework
  - genai
  - generative-ai
  - java
  - kotlin
  - llms
  - multi-agents
  - multi-agents-orchestration
  - multi-agents-system
  - spring
category: GitHub Trending
status: 未読
rating:
---

# embabel/embabel-agent

▎ JVM向けAIエージェント基盤

ライセンス: Apache-2.0
言語: Kotlin
スター数: ⭐ 4200 (+29 今日)
トレンド順位: #16 (2026-08-12)

---
## 概要

Embabelは、Springフレームワークの創始者が手がける、JVM上でエージェント型アプリケーションを構築するためのフレームワークである。単純なステートマシンではなく、GOAP(Goal Oriented Action Planning)というLLMを使わないAIアルゴリズムを用いて実行計画を動的に生成する点が最大の特徴で、「プランはプログラマではなくシステムが動的に組み立てる」という設計思想を掲げる。Action(実行ステップ)・Goal(達成したい目標)・Condition(実行前後の状態判定)・強い型付けを持つドメインモデルという概念でエージェントのふるまいをモデル化し、あらかじめ明示的にプログラムされていないタスクの組み合わせも動的に導き出せる。Spring Bootとの統合により既存のエンタープライズJavaエコシステムをそのまま活用でき、エージェントは通常のSpring Beanと同様にユニットテスト可能で、OpenTelemetryによるトレーシング(Zipkin/Langfuse対応)も標準搭載する。OpenAI・Anthropic・OCI・Ollama経由のローカルモデルなど複数のLLMプロバイダーを混在利用でき、MCPサーバーとも連携する。対象ユーザーは、PythonベースのAIエージェントフレームワークではなく、型安全性やSpringエコシステムとの親和性を重視するJava/Kotlinのエンタープライズ開発者である。

---
## 主な機能・特徴

- GOAPベースの動的プランニング — LLMを使わないAIアルゴリズムで実行計画を自動生成
- 強い型付け — 「magic map」を避けたリファクタリング可能なドメインモデル
- Spring統合 — 既存のエンタープライズJavaエコシステムをそのまま活用
- 3つの実行モード — Focused/Closed/Openで用途に応じたエージェント選択が可能
- マルチLLM対応 — OpenAI・Anthropic・OCI・Ollamaなどを柔軟に組み合わせ
- MCP連携 — Model Context Protocolサーバーとの統合
- ユニットテスト容易性 — 通常のSpring Beanと同様にテスト可能
- 組み込み可観測性 — OpenTelemetry + Zipkin/Langfuseによるトレーシング

---
## トレンド入り理由の推測

「Springの創始者が作った」という開発者の経歴自体が強い訴求力を持ち、Java/Kotlinエンタープライズ開発者コミュニティで急速に話題になったと考えられる。AIエージェントフレームワークの多くがPython/TypeScript中心で展開される中、JVMネイティブかつSpring Boot統合を前提とした設計は、既存の大規模Javaシステムを持つ企業にとって導入障壁が低く、明確な差別化要因となっている。

技術的には、単純なプロンプトチェーンやステートマシンではなく、GOAPというゲームAI分野で実績のあるプランニングアルゴリズムを採用し「プランをシステムが動的に組み立てる」という設計を前面に出している点が、他の多くのエージェントフレームワークとの差別化ポイントとして評価されている。スター数自体はまだ4.2kと大規模ではないものの、当日29という新規スターの伸びは、著名な開発者による発表やカンファレンスでの紹介、あるいはJava/Springコミュニティ内での急速な口コミ拡散を示唆している。

---
## 関連リンク

- https://github.com/embabel/embabel-agent

---
## メモ

