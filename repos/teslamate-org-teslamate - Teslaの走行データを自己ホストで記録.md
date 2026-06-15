---
url: https://github.com/teslamate-org/teslamate
saved: 2026-06-15
tags:
  - elixir
  - trending
  - docker
  - home-automation
  - mqtt
  - raspberry-pi
  - nix
  - dashboard
  - openstreetmap
  - grafana
  - tesla
  - self-hosted
  - elixir-lang
  - datalogger
  - tesla-api
  - phoenix-liveview
category: GitHub Trending
status: 未読
rating:
---

# teslamate-org/teslamate

▎ Teslaの走行データを自己ホストで記録

ライセンス: AGPL-3.0
言語: Elixir
スター数: ⭐ 8,200 (+35 今日)
トレンド順位: #2 (2026-06-15)

---
## 概要

TeslaMateはElixir製のTesla自動車専用セルフホスト型データロガーで、ドライブ記録・充電コスト追跡・地理フェンシングなどの車両データをGrafanaダッシュボードで高精度に可視化するオープンソースプロジェクト。PostgreSQLにデータを永続化し、MQTTブローカー経由でHome Assistant・Node-RED・Telegramとリアルタイム連携が可能。EV所有者がサードパーティのSaaSサービスに依存せず、プライバシーを守りながら自分の車両データを完全に管理できる自己ホスト型ソリューション。セキュリティ上の理由から公式GitHubリポジトリ以外からの取得は推奨されておらず、非公式アプリへの警告も明記されている。主なユーザー層はプライバシーを重視するTeslaオーナーやホームラボ愛好家で、Raspberry Piなど低消費電力のサーバーで常時稼働させるケースが多い。

---
## 主な機能・特徴

- 高精度ドライブデータ記録 — GPS・速度・消費電力・外気温など多様な走行データを細かく取得
- Grafanaダッシュボード — バッテリー健全性・充電効率・走行距離統計を豊富なグラフで可視化
- MQTT連携 — Home AssistantやTelegramへ車両状態をリアルタイム配信
- 地理フェンシング — 指定エリアへの到着・出発を自動認識して記録
- 充電コスト追跡 — セッションごとの充電量・コスト・所要時間を分析
- マルチ車両対応 — 複数台のTeslaを1つのインスタンスで一元管理
- TeslaFiデータインポート — 競合サービスからのデータ移行にも対応

---
## トレンド入り理由の推測

v4.0.1がJune 14, 2026にリリースされたばかりで、新バージョン公開直後のトレンド入りと考えられる。Teslaコミュニティでは新リリースが出るとRedditやTeslaフォーラムで即座に話題になり、既存ユーザーがスターを付けるとともに新規ユーザーへの口コミが広がりやすい。

AGPLv3ライセンスでSaaSへの転用を明示的に制限しており、プライバシー意識の高いオープンソースコミュニティからの強い支持を得ている。SaaSサービスの値上がりや閉鎖リスクを懸念するEVオーナーの間で、自己ホスト型ツールへの移行トレンドが加速していることも背景にある。

また、2026年時点でEVの普及が進んでいるため、TeslaMateを「はじめて試す」新規ユーザー層が拡大しており、今回のスター増加はそのような新規発見者が増えていることを示している可能性が高い。

---
## 関連リンク

- https://github.com/teslamate-org/teslamate
- https://docs.teslamate.org

---
## メモ
