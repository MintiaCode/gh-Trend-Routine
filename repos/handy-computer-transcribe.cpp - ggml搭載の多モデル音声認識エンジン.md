---
url: https://github.com/handy-computer/transcribe.cpp
saved: 2026-07-20
tags:
  - c++
  - trending
  - speech-to-text
  - asr
  - ggml
  - gguf
category: GitHub Trending
status: 未読
rating:
---

# handy-computer/transcribe.cpp

▎ ggml搭載の多モデル音声認識エンジン

ライセンス: MIT
言語: C++
スター数: ⭐ 1.2k (+401 今日)
トレンド順位: #19 (2026-07-20)

---
## 概要

transcribe.cppは、ggmlランタイム上でGGUF形式の多様な音声認識(STT)モデルを動かせるC/C++製の推論ライブラリである。Whisper、Parakeet、Canary、Moonshine、Qwen3-ASRなど16以上のモデルファミリー・60種類以上のバリエーションに対応し、Apple SiliconのMetal、Linux/Windows向けVulkan、NVIDIA向けCUDAといったGPUアクセレーションに加え、tinyBLASによるCPU最適化も備える。NVIDIA NeMoのチェックポイントをGGUF形式に変換し、F16からQ4_K_Mまでの量子化プリセットでサイズを削減しつつ、WER(単語誤り率)による数値検証で精度を担保している。Python・TypeScript・Rust・Swiftの公式バインディングも提供し、プロプライエタリなクラウドAPIに頼らず、多様なハードウェア上でオンデバイス音声認識を実現したい開発者を主な対象としている。

---
## 主な機能・特徴

- 多モデル対応 — Whisper、Parakeet、Canary、Moonshine、Qwen3-ASRなど16+ファミリー
- ストリーミング&バッチ処理 — リアルタイム/一括の両方の文字起こしに対応
- マルチバックエンド — Metal(Apple Silicon)、Vulkan(Linux/Windows)、CUDA(NVIDIA)
- 量子化モデル配布 — Hugging Face上で事前量子化済みモデルを提供
- 多言語バインディング — Python、TypeScript、Rust、Swiftの公式サポート
- 精度検証済み — 参照実装に対するWERベンチマークで数値的に検証
- 軽量コア — C++17で実装され、ggml/minizをベンダリングし依存を最小化
- NeMoモデル変換 — NVIDIA NeMoチェックポイントをGGUF形式へ変換

---
## トレンド入り理由の推測

transcribe.cppは本日+401スターと急伸しており、v0.1.3(7月12日)という直近のリリースの勢いが継続している様子がうかがえる。16以上のモデルファミリーを単一のランタイムで横断的にサポートするという範囲の広さは、特定モデル専用ツールが乱立するSTT分野において強い差別化要因となっている。

音声AI分野では、オンデバイス・プライバシー重視の推論への関心がAI業界全体で高まっており、GPU/CPUを問わず動作しWERで精度を裏付けるという実用性重視の設計が、実運用を検討するエンジニアから支持されたと考えられる。ggml/GGUFエコシステム(llama.cpp由来)の広がりも追い風となり、既存のGGUFツールチェーンに慣れたユーザーが違和感なく導入できる点も採用を後押ししている可能性が高い。

---
## 関連リンク

- https://github.com/handy-computer/transcribe.cpp
- https://huggingface.co/handy-computer

---
## メモ
