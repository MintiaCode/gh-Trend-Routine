---
url: https://github.com/microsoft/VibeVoice
saved: 2026-04-29
tags:
  - python
  - trending
category: GitHub Trending
status: 未読
rating:
---

# microsoft/VibeVoice

▎ MSオープンソース音声AIモデル

ライセンス: MIT
言語: Python
スター数: ⭐ 45626 (+1688 今日)
トレンド順位: #7 (2026-04-29)

---
## 概要

VibeVoiceは、Microsoftが開発したオープンソースのフロンティア音声AIモデルファミリーです。テキスト読み上げ（TTS）と自動音声認識（ASR）の両機能を提供します。コアとなる革新技術は、超低フレームレート（7.5Hz）で動作する連続音声トークナイザー（音響・意味の2種類）で、音声の忠実度を維持しながら長いシーケンスの計算効率を大幅に向上させています。LLMによるテキストコンテキスト理解と拡散ヘッドによる高品質音声生成を組み合わせた「next-token diffusion」フレームワークを採用しており、ICLR 2026でOral発表として採択されるなど学術的にも高く評価されています。ASRモデルはHugging Face Transformers経由でも利用可能で、50以上の言語に対応しています。

---
## 主な機能・特徴

- VibeVoice-ASR-7B — 60分の長時間音声を一括処理、話者・タイムスタンプ・内容を構造化出力
- VibeVoice-TTS-1.5B — 最大90分・4人話者の長時間多話者テキスト読み上げ
- VibeVoice-Realtime-0.5B — ストリーミングテキスト入力対応のリアルタイムTTSモデル
- 多言語対応 — ASRは50以上の言語、TTSは9言語・11種類の英語スタイルボイスをサポート
- HuggingFace統合 — Transformersライブラリから直接利用可能
- vLLM推論対応 — 高速推論のためvLLMをサポート
- Colabデモ — Google Colabですぐに試せるインタラクティブデモを提供

---
## トレンド入り理由の推測

MicrosoftがオープンソースとしてリリースしたVibeVoiceは、音声AI分野での存在感を示す重要なプロジェクトとして継続的に注目を集めています。本日+1,688スターを記録した背景として、2026年3月に実施されたHugging Face Transformersとのネイティブ統合が開発者への普及を加速していることが考えられます。ICLR 2026でOral採択という学術的評価の高さと、Microsoftという信頼性のあるブランドが、企業・研究者双方からの支持につながっています。

音声AI市場ではOpenAI WhisperやElevenLabsが先行していますが、VibeVoiceは60分超の長時間音声処理という差別化された特性を持ち、会議録音・ポッドキャスト転写・長編動画字幕生成など実用的なユースケースに強く対応しています。MITライセンスで商用利用も可能であることが、企業開発者の関心を引く要因となっています。

7.5Hzという超低フレームレートの連続音声トークナイザーという技術的な新規性も、AIエンジニアリングコミュニティでの議論を呼びやすく、テクニカルブログや論文紹介を通じた拡散が継続的なスター獲得につながっていると推測されます。

---
## 関連リンク

- https://github.com/microsoft/VibeVoice
- https://microsoft.github.io/VibeVoice/

---
## メモ

