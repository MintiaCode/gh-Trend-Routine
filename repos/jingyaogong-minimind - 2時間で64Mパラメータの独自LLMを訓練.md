---
url: https://github.com/jingyaogong/minimind
saved: 2026-08-31
tags:
  - python
  - trending
  - artificial-intelligence
  - large-language-model
category: GitHub Trending
status: 未読
rating:
---

# jingyaogong/minimind

▎ 2時間で64Mパラメータの独自LLMを訓練

ライセンス: Apache-2.0
言語: Python
スター数: ⭐ 56000 (+472 今日)
トレンド順位: #6 (2026-08-31)

---
## 概要

MiniMindは、大規模言語モデル（LLM）をゼロから完全に理解し、自分の手で訓練できるようにすることを目的とした教育・実践プロジェクトです。わずか3元（数十円）のGPUレンタル費用と約2時間の学習時間で、パラメータ数64MというGPT-3の約1/2700という超小型サイズの独自LLM「MiniMind」を、個人のGPUでも訓練・再現できます。事前学習（Pretrain）、教師ありファインチューニング（SFT）、LoRA、RLHF（DPO）、RLAIF（PPO/GRPO/CISPO）、Tool Use、Agentic RL、モデル蒸留に至るまで、LLM構築の全工程をPyTorchでフルスクラッチ実装しており、transformersなど高レベルライブラリの抽象化に頼りません。既存の巨大モデルを軽くファインチューニングするだけの「表面的な理解」ではなく、コードの一行一行からLLMの内部動作を学びたい学生・研究者・エンジニアを主な対象としています。視覚モデルMiniMind-Vやマルチモーダル版MiniMind-O、拡散言語モデル、線形注意モデルへの拡張も進んでおり、最新のQwen3系アーキテクチャに追従した構造更新も継続的に行われています。

---
## 主な機能・特徴

- 超低コスト訓練 — 3元・2時間でLLMをゼロから訓練可能
- フルスクラッチ実装 — Pretrain/SFT/LoRA/RLHF/RLAIFまで全コードを独自実装
- MoE対応構造 — Qwen3/Qwen3-MoE系に準拠したDense・MoE両対応アーキテクチャ
- Tool Use・Agentic RL — ツール呼び出しや自律的思考タグに対応した学習フロー
- 多主要フレームワーク互換 — transformers/trl/peft/llama.cpp/vllm/ollamaと連携可能
- OpenAI API互換サーバー — Open-WebUIやFastGPTなど外部Chat UIとすぐ接続可能
- 分散学習サポート — DDP/DeepSpeedによるマルチGPU訓練とwandb可視化
- 拡張実験機能 — 離散拡散言語モデルや線形注意モデルへの派生実験も収録

---
## トレンド入り理由の推測

MiniMindは2026年4月1日にminimind-3・minimind-3-moeをリリースし、構造・トークナイザー・学習パイプラインをQwen3系エコシステムに全面的に合わせて刷新しました。すでに総スター数56,000という高い実績を持つ定番プロジェクトですが、今日一日で472スターという伸びを記録しており、継続的なアップデートと教育コンテンツとしての価値の高さが安定したトレンド入りにつながっていると考えられます。

「LLMをブラックボックスとして使うのではなく、ゼロから手を動かして理解する」というコンセプトは、AIエンジニアやLLM初学者から根強い支持を集め続けています。特に、巨大モデルの微調整だけを扱う教材が氾濫する中、MiniMindのように事前学習からRLHF・RLAIF・Agentic RLまでを一気通貫でカバーする教材は希少であり、SNSや技術コミュニティでの言及・拡散が起きやすい性質を持っています。

また、動画解説やModelScopeでのオンライン体験環境も用意されており、実際に手を動かして学べる導線が整っている点も、継続的な流入を後押ししている要因と推測されます。今回の伸びは特定のバズイベントというより、教育的価値の高いリソースが中国語圏・グローバル双方の学習コミュニティで安定して紹介され続けている結果によるものと考えられます。

---
## 関連リンク

- https://github.com/jingyaogong/minimind
- https://jingyaogong.github.io/minimind

---
## メモ
