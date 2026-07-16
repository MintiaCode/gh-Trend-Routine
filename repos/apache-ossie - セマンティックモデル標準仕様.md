---
url: https://github.com/apache/ossie
saved: 2026-07-16
tags:
  - python
  - trending
  - metadata
  - semantic
category: GitHub Trending
status: 未読
rating:
---

# apache/ossie

▎ セマンティックモデル標準仕様

ライセンス: Apache-2.0
言語: Python
スター数: ⭐ 850 (+81 今日)
トレンド順位: #1 (2026-07-16)

---
## 概要

Apache Ossie(旧称 Open Semantic Interchange、OSI)は、データ分析・AI・BI領域で使われるツール群の間で「意味論(セマンティクス)」を統一的に交換するためのオープンソース仕様です。同じKPIやビジネスロジックがツールやチームごとにバラバラに定義され、手作業での突き合わせに多大な労力がかかっている現状や、定義の不整合によりAIエージェントの出力が信頼できなくなる問題を解決することを目的としています。JSON/YAMLベースのベンダー非依存な仕様として「core-spec」でスキーマを定義し、dbt・GoodData・Polaris・Salesforceなど既存の主要ツールとの相互変換コンバータや検証ツールも同梱しています。Apache Software Foundationのインキュベータープロジェクトとして開発が進められており、データエンジニア、BIツールベンダー、AIエージェント開発者など、複数ツールをまたいでデータの意味を一貫させたいすべての関係者が対象ユーザーです。

---
## 主な機能・特徴

- セマンティックモデル仕様 — JSON/YAML形式でメトリクスやディメンションの意味を定義する共通スキーマ
- core-spec — 仕様本体(spec.md)と機械可読スキーマ(spec.yaml, osi-schema.json)
- コンバータ群 — dbt、GoodData、Polaris、Salesforceなど既存フォーマットとの相互変換
- バリデーションツール — 定義したセマンティックモデルをスキーマに対して検証
- サンプル集 — TPC-DSベースの完全なセマンティックモデル例を提供
- ベンダー非依存設計 — 特定ツールに依存しない共通の「真実の源泉」を実現
- Apache Software Foundationインキュベーション — OSS標準としてのガバナンス体制

---
## トレンド入り理由の推測

今日だけで81スター、累計850スターというペースは、単発のバイラルではなく「Apache Software Foundation傘下のインキュベータープロジェクト」という後ろ盾と、旧名Open Semantic Interchange(OSI)からのリブランドが話題になったことが背景にあると考えられます。ASF入りは業界標準としての信頼性を大きく高めるため、dbt・Salesforce・GoodDataなど既存データスタックのベンダーやコミュニティで一斉に注目が集まりやすいタイミングです。

技術的な観点では、生成AIエージェントが企業データに対してクエリやレポートを生成する場面が急増する中、「同じ指標がツールごとに違う定義になっている」という長年の課題が、AIの出力信頼性に直結する問題として顕在化しています。セマンティックレイヤーの標準化はここ1〜2年でdbt Semantic LayerやCubeなど複数のプレイヤーが取り組んできたテーマであり、ASFという中立的な立場からの標準仕様提案は、ベンダーロックインを避けたい企業やOSSコミュニティにとって強い訴求力を持つため、トレンド入りしたと推測されます。

---
## 関連リンク

- https://github.com/apache/ossie
- https://ossie.apache.org/

---
## メモ
