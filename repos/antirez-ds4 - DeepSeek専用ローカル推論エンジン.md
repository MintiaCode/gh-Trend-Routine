---
url: https://github.com/antirez/ds4
saved: 2026-08-02
tags:
  - c
  - trending
  - inference
  - deepseek
  - llm
  - metal
  - cuda
  - rocm
  - gguf
  - quantization
category: GitHub Trending
status: 未読
rating:
---

# antirez/ds4

▎ DeepSeek専用ローカル推論エンジン

ライセンス: MIT
言語: C
スター数: ⭐ 19900 (+187 今日)
トレンド順位: #14 (2026-08-02)

---
## 概要

DwarfStar(ds4)は、Redis開発者として知られるantirez氏が開発した、DeepSeek V4 Flash/PROおよびGLM 5.2に特化した軽量ネイティブ推論エンジンです。汎用のGGUFランナーではなく、あえて対象モデルを絞り込むことで、モデル読み込みからプロンプト処理、ツール呼び出し、KV状態管理、HTTPサーバー、コーディングエージェントまでを一体設計・テストしている点が特徴です。Apple Silicon Mac(Metal)、NVIDIA GPU(CUDA、DGX Spark含む)、AMD Strix Halo(ROCm)など多様なハードウェアに対応し、96GB以上のメモリを持つMacではSSDストリーミングにより大型モデルの実行も可能にします。2つのMacをThunderbolt/RDMAで接続したテンソル並列や、複数マシンにレイヤーを分割するパイプライン並列など高度な分散推論もサポートし、個人所有のハイエンドPCで大規模モデルを扱いたい層をターゲットにしています。OpenAI/Anthropic互換APIサーバーを内蔵し、Claude CodeやCodex CLIなどのエージェントツールをそのまま接続できる実用性も備えています。

---
## 主な機能・特徴

- DeepSeek V4/GLM 5.2特化 — 汎用GGUFランナーではなく対象モデルを絞った専用設計
- マルチバックエンド — Metal・CUDA・ROCmに対応しMac/NVIDIA/AMDで動作
- SSDストリーミング — メモリ不足時にルーテッドエキスパートをSSDから動的読込
- 分散推論 — パイプライン並列・テンソル並列で複数マシンをまたいだ実行が可能
- OpenAI/Anthropic互換API — ds4-serverで既存エージェントツールと即座に連携
- ネイティブコーディングエージェント — KVキャッシュを直接操作する低遅延エージェント内蔵
- 投機的デコード — DSpark/MTPによる生成高速化に対応
- 詳細なベンチマーク/評価スイート — ds4-bench、ds4-evalで性能・精度を検証可能

---
## トレンド入り理由の推測

本日だけで+187スター、累計約2万スターという伸びは、著名なRedis作者antirez氏によるプロジェクトという知名度に加え、DeepSeek V4 FlashやGLM 5.2といった「ローカルで動かせる強力なオープンウェイトモデル」への関心の高さを反映しています。ローカルLLM実行環境は現在ホットな分野で、特に高性能なMac Studioやマルチ GPU 環境を持つユーザーにとって、量子化・分散推論・投機的デコードまで一気通貫でチューニングされたこのプロジェクトは希少です。

またREADMEには「GPT 5.5/5.6やClaude Fableの支援を受けて開発した」と明記されており、著名開発者によるAI協働開発の実例としても注目を集めやすい要素です。Metal/CUDA/ROCmを横断する分散・並列推論、Thunderbolt RDMA対応など、通常は大規模な推論基盤にしかない機能を個人開発として実装している点が、実利用者とローカルLLM愛好家の双方からの反響につながり、急上昇の一因になったと考えられます。

---
## 関連リンク

- https://github.com/antirez/ds4

---
## メモ
