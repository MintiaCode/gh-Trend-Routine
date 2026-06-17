---
url: https://github.com/google-research/timesfm
saved: 2026-06-17
tags:
  - python
  - trending
  - time-series
  - forecasting
  - foundation-model
  - deep-learning
  - machine-learning
category: GitHub Trending
status: 未読
rating:
---

# google-research/timesfm

▎ 時系列予測Foundation Model

ライセンス: Apache-2.0
言語: Python
スター数: ⭐ 21800 (+712 今日)
トレンド順位: #6 (2026-06-17)

---
## 概要

TimesFMは、Google Researchが開発した時系列予測に特化したデコーダーオンリー型Foundation Modelである。最新バージョン2.5では2億パラメータを搭載し、最大16Kのコンテキスト長と1Kホライズンまでの連続分位予測をサポートする。PyTorchおよびFlaxバックエンドに対応し、PyPIからの簡単なインストールが可能。事前学習済みモデルをロードするだけで、ポイント予測と分位予測の両方を生成できる。LoRAによるファインチューニング、共変量サポート（XReg）、包括的なドキュメントも提供されており、研究者から実務者まで幅広いユースケースに対応している。

---
## 主な機能・特徴

- デコーダーオンリーアーキテクチャ — 大規模事前学習による汎用的な時系列パターン理解
- 200Mパラメータ — 軽量ながら高精度な予測を実現するモデルサイズ
- 16Kコンテキスト長 — 長期間の履歴データを活用した予測が可能
- 連続分位予測 — 不確実性を含む確率的予測の出力に対応
- LoRAファインチューニング — ドメイン固有データでの効率的なモデル適応
- 共変量サポート（XReg） — 外部変数を考慮した予測の実現
- マルチバックエンド — PyTorchとFlaxの両方で動作可能
- Hugging Face統合 — モデルの簡単なダウンロードと利用

---
## トレンド入り理由の推測

1日で712スターの急増は、時系列予測分野におけるFoundation Modelの実用化が急速に進んでいることを反映している。LLMの成功に触発され、時系列データにも同様のアプローチを適用する流れが業界全体で加速しており、Google Researchという信頼性の高い開発元が提供するモデルへの関心が特に高い。

バージョン2.5での16Kコンテキスト長対応や連続分位予測といった新機能の追加が、直接的なトレンド入りのトリガーとなった可能性が高い。金融、エネルギー、小売などの業界で時系列予測の需要が拡大する中、ファインチューニング可能で軽量なFoundation Modelは実務への導入障壁を大幅に下げている。

また、AIエージェントが分析ワークフローに組み込まれる潮流の中で、時系列予測をAPIライクに呼び出せるツールへの需要が高まっており、TimesFMのようなパッケージ化されたモデルがその受け皿として注目を集めている。

---
## 関連リンク

- https://github.com/google-research/timesfm
- https://arxiv.org/abs/2310.10688
- https://huggingface.co/collections/google/timesfm-release-66e4be5fdb56e960c1e482a6

---
## メモ
