---
url: https://github.com/majd/ipatool
saved: 2026-08-30
tags:
  - go
  - trending
  - apple
  - appstore
  - cli
  - command-line
  - command-line-tool
  - golang
  - golang-library
  - ios
  - ipa
  - itunes
  - macos
  - research
  - reverse-engineering
  - security
  - swift
  - tool
category: GitHub Trending
status: 未読
rating:
---

# majd/ipatool

▎ iOSアプリipaを検索・DLするCLI

ライセンス: MIT
言語: Go
スター数: ⭐ 10,157 (+56 今日)
トレンド順位: #8 (2026-08-30)

---
## 概要

ipatoolはApp StoreからiOS・iPadOS・tvOS・visionOS向けアプリのパッケージ(ipaファイル)を検索・購入・ダウンロードできるコマンドラインツール。Apple IDで認証した上で、アプリの検索、ライセンス取得、購入済みアプリ一覧の取得、利用可能なバージョン一覧の確認、指定バージョンのipaダウンロード、バージョンメタデータの取得までを一貫してCLIから操作できる。Windows・Linux・macOSに対応しており、通常はXcodeやApp Store経由でしか行えないアプリ取得作業をスクリプト化・自動化できる点が特徴。セキュリティ研究者やリバースエンジニアがアプリバイナリを解析目的で取得する用途のほか、社内配布用アプリの旧バージョン取得やCI/CDでの自動テスト用アプリ取得など、開発者・研究者双方から利用されている。

---
## 主な機能・特徴

- auth コマンドでApple ID認証
- search コマンドでApp Store内のアプリを検索
- purchase コマンドで無料アプリのライセンスを取得
- list-purchases で購入済みアプリの一覧を表示
- list-versions で入手可能なバージョン一覧を確認
- download コマンドで指定バージョンのipaファイルを取得
- get-version-metadata でバージョンごとの詳細情報を取得
- Windows/Linux/macOSに対応したクロスプラットフォームCLI

---
## トレンド入り理由の推測

ipatoolは総スター10,157に対し本日56個の増加と、他のトレンド入りリポジトリと比べると穏やかな伸びだが、同時期に類似ジャンルのiOSリバースエンジニアリングツール(vphone-cliなど)が急上昇していることから、iOSセキュリティ・脱獄コミュニティ全体への関心の高まりに連動して再注目された可能性がある。

技術的な目新しさよりも、App Store経由でしか入手できないipaファイルをCLIで検索・ダウンロードできるという実用性の高さが継続的な支持を集めている理由と考えられ、セキュリティ研究、リバースエンジニアリング、旧バージョンアプリの保守といった需要が根強いことがうかがえる。GoによるシンプルなCLI実装で導入しやすい点も、他のセキュリティ系ツールと合わせて紹介・言及される機会を増やしている一因とみられる。

---
## 関連リンク

- https://github.com/majd/ipatool

---
## メモ

