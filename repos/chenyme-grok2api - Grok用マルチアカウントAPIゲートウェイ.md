---
url: https://github.com/chenyme/grok2api
saved: 2026-07-14
tags:
  - go
  - trending
  - grok
  - grok-imagine
category: GitHub Trending
status: 未読
rating:
---

# chenyme/grok2api

▎ Grok用マルチアカウントAPIゲートウェイ

ライセンス: MIT
言語: Go
スター数: ⭐ 5800 (+179 今日)
トレンド順位: #13 (2026-07-14)

---
## 概要

grok2apiは、xAIのGrok Build・Grok Web・Grok Consoleという3種類のGrokサービスを横断的に管理し、OpenAI互換のAPIとして公開するGo製のマルチアカウントAPIゲートウェイである。複数のGrokアカウントをプールとして管理し、優先度設定や同時実行数制限、クォータ管理、セッション維持、クールダウン、フェイルオーバーなど高度なスケジューリング機能を提供する。Device OAuth、OAuth JSON、SSO JSON、トークン一括インポートなど複数のアカウント連携方式に対応し、運用の柔軟性を高めている。Chat Completions、Images、非同期Video生成、Anthropic Messages互換など幅広いエンドポイントを標準インターフェースとして提供し、既存のOpenAI/Anthropic向けクライアントからそのまま利用できる点が特徴である。学習・研究目的での利用を想定しており、Grok APIの利用制限やアカウント管理の煩雑さを解消したい開発者やチームを主な対象としている。

---
## 主な機能・特徴

- マルチアカウントプール管理 — Grok Build/Web/Consoleを横断的に管理
- 高度なスケジューリング — 優先度・同時実行数・クォータによる制御
- セッションスティッキー・クールダウン — 安定したリクエスト処理とフェイルオーバー
- 複数のアカウント連携方式 — Device OAuth、OAuth JSON、SSO JSON、トークンインポート
- OpenAI/Anthropic互換API — Chat Completions・Images・Video・Messagesエンドポイント対応
- AES-256-GCM暗号化 — 認証情報の安全な保管とログのサニタイズ
- React製管理ダッシュボード — アカウント・モデル・APIキーを一元管理
- Docker Compose対応 — 簡単なセルフホスティングが可能

---
## トレンド入り理由の推測

grok2apiが本日急上昇した背景には、xAIのGrok関連サービス(Grok Build、Grok Web、Grok Console)の急速な普及と、それに伴うAPI利用・アカウント管理ニーズの高まりがあると考えられる。特に画像生成機能「grok-imagine」への関心の高まりが、開発者による非公式ゲートウェイ開発を後押ししている可能性が高い。

本日のスター増加数179件は総スター数5.8kの約3%に相当し、継続的に注目を集めているプロジェクトであることがうかがえる。Go言語による軽量な実装、OpenAI/Anthropic互換のAPI設計、複数アカウントの一元管理という実用性の高さが、自前でGrokベースのサービスを構築したい開発者コミュニティから支持を得ている理由と考えられる。

---
## 関連リンク

- https://github.com/chenyme/grok2api

---
## メモ

