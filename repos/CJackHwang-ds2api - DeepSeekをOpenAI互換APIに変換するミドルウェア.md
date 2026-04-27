---
url: https://github.com/CJackHwang/ds2api
saved: 2026-04-27
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

▎ DeepSeekをOpenAI互換APIに変換するミドルウェア

ライセンス: AGPL-3.0
言語: Go
スター数: ⭐ 1811 (+144 今日)
トレンド順位: #11 (2026-04-27)

---
## 概要

DS2APIは、DeepSeek Web会話機能をOpenAI・Claude（Anthropic）・Gemini互換のAPIに変換する軽量高性能フルスタックミドルウェアです。バックエンドはGo完全実装、フロントエンドはReact WebUI管理コンソールで構成されています。マルチアカウントローテーション・並行スロット管理・待機キューによる安定したAPI提供、PoW（Proof of Work）計算の純Go実装、長会話履歴のファイル化など実用的な機能を備えています。ローカル実行・Docker・Vercel Serverless・Linux systemdと多様なデプロイ方法に対応し、ワンクリックのVercel/Zeaburデプロイボタンも提供しています。学習・研究・個人実験用途向けに公開されています。

---
## 主な機能・特徴

- OpenAI・Claude・Gemini APIフォーマット全対応（マルチプロトコル変換）
- マルチアカウントローテーションによる安定したレート制限回避
- Go完全実装による高性能・低オーバーヘッドのプロキシサーバー
- Vercel Serverless・Docker・Zeaburによる簡単ワンクリックデプロイ
- React WebUI管理コンソールでアカウント・設定を視覚的に管理
- PromptCompatによるAPIリクエスト→DeepSeek Webプロトコル変換
- 長会話履歴のファイル化でコンテキストウィンドウ管理を最適化
- CORS対応・ストリーミングレスポンス（SSE）完全サポート

---
## トレンド入り理由の推測

本日144スターの増加の背景には、「DeepSeekを無料または低コストで使いたい」という持続的な開発者需要があります。pushed_atが2026-04-27T17:52:20Zと当日に更新されており、新バージョンのリリースやバグ修正があったと推測されます。DS2API v4.xという成熟したバージョン番号と、モジュール化されたアーキテクチャへの移行が、より広い開発者層への訴求につながっています。

OpenAI・Claude・Gemini三大API形式に対応するという汎用性の高さは、既存のアプリケーションをDeepSeekバックエンドへ移行したい開発者にとって魅力的です。同日トレンドの「free-claude-code」（#4）と同様のコスト削減ニーズに応えるリポジトリとして、連鎖的に発見・スターされた可能性があります。

また、Vercel/Zeaburでのワンクリックデプロイという圧倒的な手軽さが、技術的背景の異なるユーザー層を取り込んでいます。AGPL-3.0ライセンスでの公開はコミュニティへの貢献意志を示すと同時に、商用転用への制限として機能しており、個人開発者・研究者のコミュニティへの安心感を提供しています。

---
## 関連リンク

- https://github.com/CJackHwang/ds2api

---
## メモ

