---
url: https://github.com/oblien/openship
saved: 2026-07-20
tags:
  - typescript
  - trending
  - ai
  - deployments
  - self-hosted
  - agents
category: GitHub Trending
status: 未読
rating:
---

# oblien/openship

▎ AIエージェント対応の自己ホスト型デプロイ基盤

ライセンス: Apache-2.0
言語: TypeScript
スター数: ⭐ 4.6k (+1719 今日)
トレンド順位: #17 (2026-07-20)

---
## 概要

Openshipは、CI/CDを内蔵した自己ホスト型のデプロイメントプラットフォームである。リポジトリを指定するだけでスタックを自動検出し、ビルド、インフラ構成、デプロイまでを一気通貫で行い、「設定ファイルゼロ、パイプラインゼロ、YAMLゼロ」を掲げている。Node、Python、Go、Rust、PHP、Ruby、Java、.NET、Docker、モノレポなどあらゆるスタックに対応し、Postgres・MySQL・MongoDB・Redis・ワーカー・WebSocketといったバックエンドサービスも統合管理できる。SSL証明書の自動発行、CDN/HTTP3対応のエッジキャッシュ、DKIM/SPF/DMARC設定済みのメールサーバー、スケジュールバックアップとワンクリック復元、ビルドログやコンテナメトリクスのリアルタイム監視まで、インフラ運用を丸ごと肩代わりする。デスクトップアプリ・Webダッシュボード・CLIに加えREST APIとMCPプロトコルを提供し、AIエージェントからの自動デプロイにも対応する。VercelやRailwayのような体験を自前のVPSで実現したい開発者やスタートアップが主な対象である。

---
## 主な機能・特徴

- ゼロコンフィグデプロイ — リポジトリを指すだけでスタックを自動検出しビルド・デプロイ
- 幅広い言語/ランタイム対応 — Node、Python、Go、Rust、PHP、Ruby、Java、.NET、Dockerなど
- 統合バックエンドサービス — Postgres、MySQL、MongoDB、Redis、ワーカー、WebSocket
- 自動インフラ管理 — SSL自動発行、CDN/エッジキャッシュ、メールサーバー設定
- バックアップ&復元 — スケジュールバックアップとワンクリックロールバック
- 多様なデプロイ先 — Openship Cloud、任意のVPS、専用サーバー、マルチノード構成
- 複数のアクセス手段 — デスクトップアプリ、Webダッシュボード、CLI
- AIエージェント連携 — REST APIとMCPプロトコルによる自動化対応

---
## トレンド入り理由の推測

openshipは本日+1719スターと今回調査した中でも際立った急伸を見せている。最大の要因は「セルフホストで動かせるVercel/Railway代替」という明確な価値提案にあると考えられる。クラウドサービスのコスト増や依存リスクを懸念する開発者にとって、YAMLもパイプライン設定も不要という手軽さは強い訴求力を持つ。

もう一つの要因として、REST APIとMCPプロトコルによるAIエージェント連携が挙げられる。2026年に入りAIコーディングエージェントが自律的にアプリをデプロイするワークフローへの関心が急速に高まっており、「AIエージェントからワンクリックでデプロイできるプラットフォーム」という位置づけがタイムリーに刺さった可能性が高い。直近のv0.1.11リリース(7月18日)というごく最近のアップデートも、Trending入りのタイミングと符合している。

---
## 関連リンク

- https://github.com/oblien/openship
- https://openship.io

---
## メモ
