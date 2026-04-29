---
url: https://github.com/soxoj/maigret
saved: 2026-04-29
tags:
  - python
  - trending
  - blueteam
  - cli
  - cybersecurity
  - identification
  - infosec
  - investigation
  - namechecker
  - open-source
  - osint
  - osint-framework
  - osint-python
  - pentesting
  - python
  - python3
  - reconnaissance
  - redteam
  - scraping
  - sherlock
  - social-network
  - socmint
category: GitHub Trending
status: 未読
rating:
---

# soxoj/maigret

▎ ユーザー名から3000+サイト調査ツール

ライセンス: MIT
言語: Python
スター数: ⭐ 20188 (+31 今日)
トレンド順位: #13 (2026-04-29)

---
## 概要

Maigretは、ユーザー名のみを入力するだけで3,000以上のサイトにわたるアカウント調査・個人情報収集を行うOSINTツールです。APIキー不要で動作し、`pip install maigret && maigret USERNAME`の2コマンドで即座に使い始められます。デフォルトではトラフィック上位500サイトを検索し、`-a`オプションで全サイトをスキャン可能です。プロフィールページとサイトAPIから利用可能な全情報を抽出し、発見した他のユーザー名・IDを使って再帰的に検索を深めます。Torおよびi2pサイトにも対応しており、ブロック・検閲・CAPTCHAの部分的な回避機能も持ちます。Telegram Bot・Cloud Shell・Webインターフェース（グラフ表示）でも利用でき、複数形式のレポートをエクスポートできます。

---
## 主な機能・特徴

- 3,000+サイト対応 — ソーシャルメディア・フォーラム・専門サービスを横断的に検索
- APIキー不要 — pip installするだけですぐに使えるゼロ設定設計
- 再帰的検索 — 発見したユーザー名・IDを使って自動的に検索を深掘り
- Tor/I2P対応 — 匿名ネットワーク上のサイトも調査可能
- Webインターフェース — グラフ形式でアカウント関係を可視化し各種形式でレポート出力
- Pythonライブラリとして使用可能 — importしてプログラム内から検索を呼び出せる
- 自動更新サイトデータベース — 24時間ごとにGitHubからサイト一覧を自動取得

---
## トレンド入り理由の推測

Maigretは本日+31スターと少ないながらも、pushed_atが2026-04-29T15:20:45Zと当日更新されていることから、新機能追加やバグ修正のリリースがあったと考えられます。OSINT・サイバーセキュリティコミュニティでは定番の調査ツールとして確立されており、セキュリティ研究者や法執行機関向けのプロOSINTツール（Social Links API・Crimewall等）にも採用されています。

GhostTrackと同様、今日はOSINT系ツール全体への注目度が高まっていることがトレンド入りの背景にあると推測されます。ユーザー名一本でソーシャルメディア上の全足跡を追えるという機能は、企業のデューデリジェンス・デジタルフォレンジック・ペネトレーションテストなど多様な業務用途に対応しており、継続的な需要を生み出しています。

MIT ライセンスでPyPI経由でも配布されており、Python開発者にとって導入の敷居が極めて低い点が長期的な普及を支えています。Sherlockなど同種のツールを知るOSINTコミュニティからのクチコミ流入も、安定したスター獲得の要因になっています。

---
## 関連リンク

- https://github.com/soxoj/maigret
- https://maigret.readthedocs.io

---
## メモ

