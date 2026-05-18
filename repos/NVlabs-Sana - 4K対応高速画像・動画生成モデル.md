---
url: https://github.com/NVlabs/Sana
saved: 2026-05-18
tags:
  - python
  - trending
  - reinforcement-learning
  - transformers
  - pytorch
  - diffusion
  - dit
  - video-generation
  - sana
  - text-to-video
  - linear-transformer
  - text-to-image-generation
  - system-algorithm-design
  - nvfp4
category: GitHub Trending
status: 未読
rating:
---

# NVlabs/Sana

▎ 4K対応高速画像・動画生成モデル

ライセンス: Apache-2.0
言語: Python
スター数: ⭐ 6400 (+376 今日)
トレンド順位: #12 (2026-05-18)

---
## 概要

NVIDIA Labsが開発する高解像度画像・動画生成フレームワーク。線形拡散トランスフォーマーを採用し、Flux-12Bと比較して20分の1の規模でありながら100倍の速度を実現する。4K解像度までのテキストから画像生成、720p・最長1分間の動画生成に対応。SANA-Sprintモデルは1ステップ生成で1024pxの画像をH100上で0.1秒で生成可能。DC-AEによる32倍の画像圧縮と線形アテンション機構により、VRAM 8GB未満のラップトップGPUでも4ビット量子化を通じて動作する。Hugging Face Diffusers・ComfyUI・SGLangとの統合で多様なデプロイ環境に対応。SANA、SANA-1.5、SANA-Sprint、SANA-Video、SANA-WM、Sol-RLなど複数のバリアントを提供する。

---
## 主な機能・特徴

- 線形拡散トランスフォーマー — 標準アテンション機構を線形アテンションで置き換えて大幅高速化
- SANA-Sprint — 1ステップ生成で1024px画像をH100上で0.1秒で生成する超高速モデル
- 4K画像生成 — 最大4K解像度のテキストから画像生成をサポート
- 動画生成対応 — 720p・最長1分間の動画生成（SANA-WM: 2.6Bパラメータ世界モデル）
- DC-AE圧縮 — 従来の8倍に対し32倍の画像圧縮技術で効率的な推論を実現
- 低VRAM動作 — 4ビット量子化でVRAM 8GB未満のGPUでも実行可能
- 強化学習後処理 — Sol-RLによる4.64倍速い収束の強化学習ポストトレーニング

---
## トレンド入り理由の推測

NVIDIA Labsによる公式リポジトリであること、かつ動画生成モデル（SANA-Video・SANA-WM）の追加により、テキストから画像・動画への統合ソリューションとして本日改めて注目されたと推測される。「Flux-12Bの100倍速」という具体的な性能比較が技術者の興味を引き、X（旧Twitter）やHacker Newsでの拡散につながった可能性が高い。4ビット量子化でラップトップGPU（8GB VRAM未満）でも動作するという低リソース対応が、高性能GPUを持たない一般開発者・研究者の参入障壁を大幅に下げている点も支持拡大に寄与している。

2025年3月の最新リリース（SANA-1.5・SANA-Sprint）から約2ヶ月が経過し、コミュニティでの活用事例が蓄積されてきたことで今週のトレンド入りにつながったと考えられる。画像・動画生成AI分野での競争激化（Sora・Wan・HunyuanVideoとの比較）において、オープンソースで高速・軽量な選択肢として差別化された存在感を放っている。

ComfyUIとの統合によるクリエイター向けワークフローへの組み込みの容易さ、およびHugging Face Diffusersとの統合による開発者フレンドリーなAPIが、幅広い支持層を形成している。NVIDIAブランドへの信頼性と研究品質の高さが、個人開発者から企業の本番利用まで多様な需要に対応できる信頼性を裏付けている。

---
## 関連リンク

- https://github.com/NVlabs/Sana
- https://nvlabs.github.io/Sana/docs/

---
## メモ

