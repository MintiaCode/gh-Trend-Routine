---
url: https://github.com/microsoft/VibeVoice
saved: 2026-04-27
tags:
  - python
  - trending
category: GitHub Trending
status: 未読
rating:
---

# microsoft/VibeVoice

▎ Microsoftオープンソース音声AIフレームワーク

ライセンス: MIT
言語: Python
スター数: ⭐ 42990 (+771 今日)
トレンド順位: #8 (2026-04-27)

---
## 概要

VibeVoiceは、Microsoftが開発・公開したオープンソースのフロンティア音声AIモデルファミリーです。テキスト読み上げ（TTS）と自動音声認識（ASR）の両モデルを含みます。コア技術として7.5Hzの超低フレームレートで動作する連続音声トークナイザー（音響・意味）を採用し、長時間音声処理の計算効率を大幅に向上させています。VibeVoice-TTS（1.5B）は最大90分・4話者のマルチスピーカーTTSを実現し、ICLR 2026でOral発表された研究成果です。VibeVoice-ASR（7B）は50以上の言語対応で60分の長時間音声を一括処理し、話者・タイムスタンプ・内容を構造化出力します。HuggingFace Transformersライブラリへの統合も完了しており、実用的な音声AIアプリ開発に直接活用できます。

---
## 主な機能・特徴

- VibeVoice-TTS：最大90分・4話者対応のマルチスピーカーテキスト読み上げ（ICLR 2026 Oral）
- VibeVoice-ASR：60分長時間音声を一括処理する統合音声認識（50以上の言語対応）
- VibeVoice-Realtime-0.5B：ストリーミングテキスト入力対応のリアルタイムTTSモデル
- 7.5Hzの超低フレームレート音声トークナイザーによる高効率長文処理
- Next-token diffusionフレームワーク（LLM＋拡散ヘッド）による高品質音声生成
- HuggingFace Transformers直接統合でシームレスな既存パイプライン組み込み
- vLLM推論対応による高速インファレンス
- Gradio Playgroundでのブラウザ体験・Google Colabでのワンクリック試用

---
## トレンド入り理由の推測

本日771スターの増加は、2026年3月にVibeVoice-ASRがHuggingFace Transformersに統合されたことによる継続的な注目の蓄積と、音声AI市場全体の盛り上がりが重なった結果です。pushed_atは2026-04-24と数日前であり、直近の機能追加よりも「音声AI」というカテゴリへの市場関心の高まりがトレンドの主因と考えられます。

Microsoftという信頼性の高いブランドによるオープンソース公開であること、ICLR 2026でのOral採択という学術的権威、そして無料で使えるPlaygroundとColabデモの存在が、研究者・開発者双方へのアクセシビリティを高めています。「90分のマルチスピーカーTTS」という従来の短文TTSを大きく超えるスペックが話題性を持続させています。

また、Whisperなど既存のOSS音声AIとは異なる「長時間・マルチスピーカー・多言語」という三拍子の組み合わせ、さらにリアルタイムストリーミングTTSモデルまで揃えた完全なVoice AIスイートとしての完成度が、企業・スタートアップのアーキテクチャ選定においてVibeVoiceを強力な候補として浮上させていると推測されます。

---
## 関連リンク

- https://github.com/microsoft/VibeVoice
- https://microsoft.github.io/VibeVoice/

---
## メモ

