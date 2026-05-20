---
url: https://github.com/rmyndharis/OpenWA
saved: 2026-05-20
tags:
  - typescript
  - trending
  - api
  - gateway
  - whatsapp
category: GitHub Trending
status: 未読
rating:
---

# rmyndharis/OpenWA

▎ セルフホスト型WhatsApp APIゲートウェイ

ライセンス: MIT
言語: TypeScript
スター数: ⭐ 4700 (+726 今日)
トレンド順位: #11 (2026-05-20)

---
## 概要

「OpenWA」は、無料・オープンソースのセルフホスト型WhatsApp APIゲートウェイです。NestJSフレームワークとwhatsapp-web.jsエンジンを基盤に、REST APIによるWhatsAppメッセージング操作を提供します。マルチアカウントセッション管理、リアルタイムWebhookイベント配信、React製管理ダッシュボード、Swagger APIドキュメントを内蔵し、エンタープライズ級のメッセージング機能をセルフホスト環境で実現します。データベースはSQLiteまたはPostgreSQL、ストレージはローカルまたはS3互換オブジェクトストレージ、キャッシュはRedis（オプション）と高い柔軟性を持ち、設定ファイルの変更だけでインフラ構成を切り替え可能です。Dockerコンテナ化により迅速なデプロイが可能で、テキスト・メディア送受信、メッセージリアクション、一括操作、配信追跡、グループ・チャンネル管理など包括的なWhatsApp機能を提供します。WhatsApp Business APIの高額費用や制限を回避したい開発者・企業に向けたソリューションです。

---
## 主な機能・特徴

- REST API — WhatsAppメッセージング操作をRESTful APIで提供
- マルチアカウント管理 — 複数WhatsAppセッションの同時管理
- Webhookイベント — リアルタイムメッセージ受信・状態変化通知
- 管理ダッシュボード — React製WebUIでアカウント・メッセージを管理
- 柔軟なインフラ — SQLite/PostgreSQL・ローカル/S3・Redisの自由な組み合わせ
- Docker対応 — コンテナによる簡単デプロイ
- 豊富なメッセージ機能 — テキスト・メディア・リアクション・一括送信・グループ管理

---
## トレンド入り理由の推測

4,700スターに対して726スター/日という急激な増加は、WhatsApp自動化ニーズの高まりを反映しています。公式のWhatsApp Business APIは月額固定費や1通あたり課金など高コストで中小企業には敷居が高く、OSSのセルフホスト代替として本プロジェクトへの関心が集中したと考えられます。

Node.js 22 LTSとNestJS 11.xという2026年現在の最新スタックへの対応と、v0.1.6という安定版リリースが2026年5月17日（3日前）にリリースされており、これが本日のトレンド入りの直接的なきっかけと推測されます。リリースノートの拡散やプロダクトハント等での紹介が急激なスター増加につながったと考えられます。

WhatsApp自動化はCRM連携、カスタマーサポートBot、OTP認証など多様なビジネスユースケースがあり、セルフホスト可能な無料ソリューションへの需要は世界的・特に新興市場で非常に旺盛です。Dockerサポートにより参入障壁が下がり、幅広い開発者層に広まったと推測されます。

---
## 関連リンク

- https://github.com/rmyndharis/OpenWA
- https://www.open-wa.org

---
## メモ
