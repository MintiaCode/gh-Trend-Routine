---
url: https://github.com/apache/maka
saved: 2026-08-23
tags:
  - typescript
  - trending
  - agent-runtime
  - ai
  - ai-agent
  - apache
  - cli
  - desktop
  - electron
  - event-sourcing
  - incubator
  - llm
  - local-first
  - maka
  - tool-use
  - typescript
category: GitHub Trending
status: 未読
rating:
---

# apache/maka

▎ ローカルファーストAIエージェント基盤

ライセンス: Apache-2.0
言語: TypeScript
スター数: ⭐ 2300 (+49 今日)
トレンド順位: #7 (2026-08-23)

---
## 概要

Apache Maka(インキュベーション中)は、Apache Software Foundationのインキュベータで開発が進むローカルファーストのAIエージェントワークスペースです。デスクトップアプリ(Electron+React)、ターミナル/CLI、評価(Eval)フレームワークという3つの入り口を持ちながら、すべて「Runtime Host」という単一の実行基盤を経由することで、セッションやモデル接続、権限設定を一元管理しています。最大の特徴は、モデルとのメッセージやツール呼び出し、ターンの終了理由までを「復元可能な実行事実(execution facts)」としてローカルに記録する設計思想で、UIや次のモデル呼び出しはその記録のビューに過ぎない、という考え方を採用しています。コンテキストを短縮しても証跡は失われず、クラッシュからの復旧や中断したターンの再開も可能です。ツールがサンドボックスの外に出る操作は承認制で、Read/Write/Edit/Bash/Glob/Grepなどの組み込みツールを備えます。自分のマシン上でデータを保持しつつ、クラウドAPIやローカルモデルなど好きなモデルを組み合わせて使いたい開発者やチームを対象としています。

---
## 主な機能・特徴

- Runtime Host — デスクトップ・CLI・Evalすべてが同じ実行基盤を共有
- 復元可能な実行記録 — モデルメッセージ・ツール呼び出し・終了理由を保存
- サンドボックス境界 — サンドボックス外に出るツール操作は承認制
- 組み込みツール — Read, Write, Edit, Bash, Glob, Grepを標準搭載
- クラッシュ復旧・ターン再開 — 中断した処理を保存済み記録から再開可能
- 宣言的な評価(Eval)フレームワーク — task×repetition×subjectのセルで再現性のあるベンチマーク
- デスクトップワークスペース — セッションの分岐・検索・再実行・アーカイブに対応
- Apache Software Foundationインキュベーション中プロジェクト

---
## トレンド入り理由の推測

Apache Makaは本日49件と獲得スター数自体は控えめですが、トレンド入りした背景には「Apache Software Foundation」という中立的で信頼性の高い組織のもとでインキュベーションが始まったばかりという新規性があります。ASFプロジェクトとしての発表は開発者コミュニティで注目を集めやすく、公開直後のリポジトリとして急上昇しやすい傾向があります。

技術的には、ローカルファーストでエージェントの実行記録を「消えない証跡」として保持するという設計が、OpenAI Codexやその他のAIコーディングエージェントが乱立する中での差別化ポイントになっています。デスクトップ・CLI・評価基盤を単一のRuntime Hostに統合するアーキテクチャは、AIエージェントツールの信頼性・再現性・監査可能性が課題視され始めている現在の業界動向とも合致しています。

またmacOS Apple Silicon向けの早期パブリックリリースというタイミングも、Mac中心の開発者層からの注目を集めやすい要因と考えられます。

---
## 関連リンク

- https://github.com/apache/maka

---
## メモ

