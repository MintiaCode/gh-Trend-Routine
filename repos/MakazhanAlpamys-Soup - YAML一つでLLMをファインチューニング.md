---
url: https://github.com/MakazhanAlpamys/Soup
saved: 2026-08-15
tags:
  - python
  - trending
  - cli
  - consumer-gpu
  - dpo
  - fine-tuning
  - gguf
  - huggingface
  - llm
  - llmops
  - local-ai
  - local-llm
  - lora
  - low-vram
  - machine-learning
  - ollama
  - peft
  - pytorch
  - qlora
  - sft
  - transformers
category: GitHub Trending
status: 未読
rating:
---

# MakazhanAlpamys/Soup

▎ YAML一つでLLMをファインチューニング

ライセンス: Apache-2.0
言語: Python
スター数: ⭐ 1600 (+303 今日)
トレンド順位: #7 (2026-08-15)

---
## 概要

SoupはLLMのファインチューニングと事後学習(post-training)を、SSH接続もクラウドインフラ構築も不要で、単一のYAML設定ファイルだけで実行できるCLIツールである。「Zero SSH. One config. Auto everything.」を掲げ、環境構築の煩雑さを排除して手元のPCから直接学習を始められることを目指している。最大の特徴は「レイヤーストリーミング」技術で、凍結されたモデルレイヤーをRAMからGPUへ1層ずつストリーミングすることで、わずか4GBのVRAMしかないノートPC用GPUでも8Bパラメータ級のモデルを学習可能にしている。対応する学習手法はSFT(教師ありファインチューニング)に加えDPO・ORPO・SimPOなどの選好学習(preference learning)にも及び、HuggingFace Hub上のCausalLM系モデルであれば幅広く利用できる。ターゲットユーザーは、高価なクラウドGPUを持たない個人開発者や研究者、ローカル環境でプライバシーを保ちながらLLMをカスタマイズしたい層である。

---
## 主な機能・特徴

- レイヤーストリーミング — 4GB VRAMのノートPCで8Bモデルの学習を実現(RTX 3050 Laptopで3.32GBピーク・119.6 tok/sの実測値)
- 単一YAML設定 — 複雑なコード記述なしに学習パイプラインを定義
- 多様な学習手法対応 — SFT、DPO、ORPO、SimPOなど選好学習を含む複数手法をサポート
- QLoRA/LoRA/PEFT対応 — 省メモリな量子化学習に幅広く対応
- モデル互換性 — HuggingFace Hub上のCausalLMモデルを広くサポート
- マージ・エクスポート・配信機能 — 学習後のモデルをGGUF変換やOllama連携などで即座に活用可能
- 軽量CLIから本格構成まで選択可能 — soup-cliのみのインストールからUI付きフル構成まで段階的に導入できる

---
## トレンド入り理由の推測

総スター数1600に対し今日303スターを獲得しており、総数の約19%が1日で積み上がっている急伸パターンである。ローカルLLMのファインチューニングというテーマ自体はここ数年安定した需要があるが、既存ツール(Axolotl、Unslothなど)と比べ「4GBのノートPC用GPUで8Bモデルを学習できる」という具体的かつ強烈な数値インパクトが、SNSや技術コミュニティで一気に拡散した要因と考えられる。

同日のトレンドリストにunslothai/unslothというローカルLLM学習・実行ツールも入っていることから、ローカル環境でのAIモデルカスタマイズへの関心が業界全体で高まっているタイミングと重なったことも追い風になっていると推測される。高価なクラウドGPU課金を避けて手元のマシンでLLMを育てたいという開発者のニーズに、「Zero SSH. One config.」という分かりやすい訴求が刺さり、話題性を獲得したと考えられる。

---
## 関連リンク

- https://github.com/MakazhanAlpamys/Soup
- https://trysoup.dev

---
## メモ
