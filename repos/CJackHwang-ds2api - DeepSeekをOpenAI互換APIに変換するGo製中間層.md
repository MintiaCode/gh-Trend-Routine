---
url: https://github.com/CJackHwang/ds2api
saved: 2026-04-28
tags:
  - go
  - trending
  - api
  - claude-api
  - deepseek
  - deepseek-api
  - docker
  - freeapi
  - openai-api
  - proxy
  - proxy-server
  - react
  - vercel
  - vercel-deployment
  - zeabur
category: GitHub Trending
status: 未読
rating:
---

# CJackHwang/ds2api

▎ DeepSeekをOpenAI互換APIに変換するGo製中間層

ライセンス: AGPL-3.0
言語: Go
スター数: ⭐ 2293 (+418 今日)
トレンド順位: #9 (2026-04-28)

---
## 概要

ds2apiは、DeepSeekのウェブ会話機能をOpenAI・Claude・Gemini互換のAPI形式に変換する軽量・高性能なフルスタックミドルウェアです。Go言語のバックエンドとReactフロントエンドで構成され、マルチアカウントローテーション・自動トークンリフレッシュ・同時実行キュー管理などを備えています。コンパイル済みバイナリ・Docker・Vercel Serverlessなど複数のデプロイオプションに対応し、単一のconfig.jsonで設定が完結します。ただし、本プロジェクトは学習・研究・個人実験目的のみを対象としており、商用利用やアカウント停止のリスクに対する免責が明示されています。

---
## 主な機能・特徴

- 3フォーマット対応 — OpenAI・Claude・Gemini API形式すべてに互換
- マルチアカウントローテーション — 複数アカウントの自動切り替えとトークンリフレッシュ
- Go製PoWアルゴリズム — DeepSeekのProof-of-WorkをGoで純粋実装
- ツールコール対応 — リーク防止と構造化出力のハンドリングを含む
- 管理WebUI — バイリンガル対応のReactダッシュボード
- 複数デプロイ形態 — バイナリ・Docker・Vercel・ソースコンパイルに対応
- モデルエイリアス — claude-sonnet-4-6 → deepseek-v4-flashなどの変換マッピング

---
## トレンド入り理由の推測

今日だけで418スターを獲得したds2apiがトレンド入りした背景には、AIAPIコストの高騰とDeepSeekの人気があります。Claude・OpenAI・Gemini互換のAPIフォーマットで実際には無料のDeepSeekウェブ版を呼び出せるという点が、APIコストを節約したい開発者に強く響いています。

pushed_atが本日（2026年4月28日）であることも重要な要因です。当日の更新・リリースがHacker NewsやRedditなどのコミュニティに拾われ、一気に注目を集めた可能性が高いです。Go製でバイナリ配布に対応しているため、セットアップの容易さも拡散を後押ししました。

ただし、本プロジェクトは「学習・研究目的のみ」と明言しており、実際にはDeepSeekの利用規約に抵触する可能性があります。このグレーゾーンな性質がかえって開発者の関心を集め、「試してみたい」という動機付けにつながったとも考えられます。

---
## 関連リンク

- https://github.com/CJackHwang/ds2api

---
## メモ
