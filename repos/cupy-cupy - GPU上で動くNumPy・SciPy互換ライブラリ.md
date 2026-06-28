---
url: https://github.com/cupy/cupy
saved: 2026-06-28
tags:
  - python
  - trending
  - cublas
  - cuda
  - cudnn
  - cupy
  - curand
  - cusolver
  - cusparse
  - cusparselt
  - cutensor
  - gpu
  - nccl
  - numpy
  - nvrtc
  - nvtx
  - rocm
  - scipy
  - tensor
category: GitHub Trending
status: 未読
rating:
---

# cupy/cupy

▎ GPU上で動くNumPy・SciPy互換ライブラリ

ライセンス: MIT
言語: Python
スター数: ⭐ 11459 (+172 今日)
トレンド順位: #7 (2026-06-28)

---
## 概要

CuPyは、NumPyおよびSciPyのAPIと互換性を持つGPUアクセラレーション配列ライブラリである。既存のNumPy/SciPyコードをほぼそのままNVIDIA CUDAまたはAMD ROCmプラットフォーム上で実行できる「ドロップイン置き換え」として設計されている。基本的な配列演算に加えて、RawKernelsによる既存CUDAプログラムとの連携、Streamsによるパフォーマンス最適化、CUDA Runtime APIへの直接アクセスなど、低レベルGPU機能も提供する。pip、conda-forge、Dockerなど複数のインストール方法に対応し、CUDA 12.x/13.xおよびROCm 7.0をサポートしている。科学計算、機械学習、データ分析においてGPUの並列処理能力を活用したい研究者やエンジニアに最適なツールである。

---
## 主な機能・特徴

- ドロップイン互換性 — 既存NumPy/SciPyコードをほぼ無修正でGPU実行
- マルチプラットフォーム — NVIDIA CUDA・AMD ROCm両対応
- RawKernels — カスタムCUDAカーネルとの直接連携
- Streams最適化 — GPU演算のパフォーマンスチューニング
- 豊富なCUDAライブラリ統合 — cuBLAS、cuDNN、cuSOLVER等を内蔵
- 柔軟なインストール — pip、conda-forge、Docker対応
- NCCL対応 — マルチGPU分散計算サポート

---
## トレンド入り理由の推測

CuPyは成熟したライブラリだが、AI・LLMブームの中でGPUコンピューティングへの需要が爆発的に増加しており、NumPy互換のGPUライブラリとしての価値が再認識されている。特にLLMの学習・推論パイプラインにおいて、データ前処理や数値計算のGPU化ニーズが高まっていることが、トレンド入りの背景にある。

pushed_atが2026年6月28日の当日であり、活発な開発が継続していることを示している。総スター数11,459に対して今日172スターの獲得は約1.5%だが、成熟プロジェクトとしては大きなスパイクである。CUDA 13.xやROCm 7.0など最新GPU環境への対応が進んでいることから、新しいGPUハードウェアの発売や、大手クラウドプロバイダーの環境更新に伴う注目の再燃が考えられる。

---
## 関連リンク

- https://github.com/cupy/cupy
- https://cupy.dev

---
## メモ
