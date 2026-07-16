---
url: https://github.com/PrismML-Eng/Bonsai-demo
saved: 2026-07-16
tags:
  - shell
  - trending
  - bonsai
  - mlx
  - llm
  - small-models
  - llamacpp
  - prism-ml
category: GitHub Trending
status: 未読
rating:
---

# PrismML-Eng/Bonsai-demo

▎ 1-bit軽量LLMをローカル実行

ライセンス: Apache-2.0
言語: Shell
スター数: ⭐ 1500 (+323 今日)
トレンド順位: #6 (2026-07-16)

---
## 概要

Bonsai-demoは、極端に量子化された「Bonsai」(1-bit)および「Ternary-Bonsai」言語モデルを、Mac(Metal)・Linux/Windows(CUDA、Vulkan、ROCm)・CPUでローカル実行するためのデモリポジトリです。通常のLLMはメモリ消費が大きくクラウド依存になりがちですが、Bonsaiシリーズは1重み当たり約1.125〜1.7ビットまで圧縮しており、最大モデルの27Bでもスマートフォン(iPhone)に載るほど軽量です。最新の「Bonsai 27B」は同ファミリー初のビジョン言語モデルであり、写真・スクリーンショット・PDFの理解、OpenAI互換のツールコール(MCPサーバー対応)、推論強度を調整できる思考モード、25万トークン超のロングコンテキストにも対応します。セットアップスクリプト一つでモデルのダウンロードから起動まで完結し、ローカル推論やエッジデバイスでのAI活用を目指す開発者・研究者・プライバシー重視のユーザーを対象としています。

---
## 主な機能・特徴

- 1-bit/Ternary量子化 — 重み当たり約1.125〜1.7ビットの超軽量モデル
- Bonsai 27B — ファミリー最大・最新でビジョン対応の主力モデル
- マルチプラットフォーム — Mac(Metal)、Linux/Windows(CUDA・Vulkan・ROCm)、CPUで動作
- ビジョン機能 — 画像・スクリーンショット・PDFを渡して質問可能
- エージェント機能 — OpenAI形式のtool_callsとMCPサーバー統合
- 思考モード — 推論の強度(reasoning effort)をチャットごとに調整可能
- ロングコンテキスト — 25万トークン以上の会話に対応
- ワンコマンドセットアップ — setup.shで依存関係・モデル・バイナリを一括導入

---
## トレンド入り理由の推測

今日だけで323スター増(累計1,500)という急伸ぶりは、READMEにある「🌱 New: Bonsai 27B」という新モデル発表のタイミングと一致しており、新規リリース直後の話題性がそのままGitHubスターの急増に直結したと考えられます。1-bit/ternary量子化という極端な圧縮技術で最大級モデルをスマートフォンに載せられる点は、ローカルLLM/エッジAIブームの中でも特に強いインパクトを持つ技術デモです。

さらに、ビジョン対応・エージェント型ツールコール・MCPサーバー統合・思考モードといった、直近のLLMトレンドをほぼ網羅した機能を「軽量ローカルモデル」で実現している点が、開発者コミュニティの関心を強く引いたと推測されます。llama.cpp/MLXエコシステムとの親和性や、HuggingFaceでのモデル公開、Discordコミュニティの存在も、SNSや技術系ニュースレターでの拡散を後押しした要因と考えられます。

---
## 関連リンク

- https://github.com/PrismML-Eng/Bonsai-demo
- https://prismml.com

---
## メモ
