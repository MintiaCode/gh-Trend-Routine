---
url: https://github.com/Zackriya-Solutions/meetily
saved: 2026-07-04
tags:
  - rust
  - trending
  - windows
  - mac
  - ai
  - offline-first
  - self-hosted
  - speech-to-text
  - transcription
  - whisper
  - meeting-minutes
  - meeting-notes
  - privacy-tools
  - parakeet
  - privacy-focused
  - llm
  - whisper-cpp
  - local-ai
  - ollama
  - ai-meeting-assistant
  - sortformer
category: GitHub Trending
status: 未読
rating:
---

# Zackriya-Solutions/meetily

▎ ローカル完結型AI会議アシスタント

ライセンス: MIT
言語: Rust
スター数: ⭐ 15000 (+865 今日)
トレンド順位: #6 (2026-07-04)

---
## 概要

Meetilyは、会議の録音・文字起こし・要約をすべてローカル環境で完結させるプライバシー重視のオープンソースAI会議アシスタントである。クラウドAPIへの音声送信を必要とせず、WhisperやNVIDIA Parakeetモデルによるリアルタイム音声認識、話者分離(スピーカーダイアライゼーション)、Ollama等を用いたローカルLLMによる要約生成までを一台のマシン上で処理する。企業のデータ漏洩リスクやGDPR等のコンプライアンス違反、サブスクリプション型AI議事録サービスの継続コストを懸念する個人・チームを主なターゲットとし、Rust製バックエンドとTauri/Next.jsによるクロスプラットフォーム対応(macOS・Windows・Linux)で、Apple SiliconやNVIDIA/AMD GPUによるハードウェアアクセラレーションも活用できる。MITライセンスのコミュニティ版は永続的に無料で提供され、より高精度な文字起こしや高度なエクスポート機能を備えた有料のPRO版も用意されている。

---
## 主な機能・特徴

- リアルタイム文字起こし — Whisper/Parakeetモデルによる高速(4倍速)音声認識
- 完全ローカル処理 — 音声データを一切クラウドに送信しない設計
- 話者分離(ダイアライゼーション) — 発言者ごとに自動で発言を区別
- ローカルLLM要約 — Ollama等を用いてクラウド不要で議事録を自動生成
- マルチプラットフォーム対応 — macOS/Windows/Linuxで動作するTauriベースアプリ
- ハードウェアアクセラレーション — Apple SiliconやNVIDIA/AMD GPUに対応
- 外部AIプロバイダ連携も選択可能 — Claude、Groq、OpenRouterなどとの統合オプション
- MITライセンスの無料版と高機能PRO版を提供

---
## トレンド入り理由の推測

このリポジトリは本日865個のスターを獲得しており、累計1.5万スターに対して1日で高い伸び率を記録している。これは近年のリモートワーク普及に伴う会議記録ニーズの高まりと、AI議事録ツールに対する「データを外部に送りたくない」というプライバシー意識の高まりが背景にあると考えられる。ZoomやOtter.aiなど既存のクラウド型会議アシスタントに対する不信感や、企業の情報漏洩リスク回避の観点から、完全ローカルで完結するMeetilyのようなツールへの関心が急速に高まっている。

技術的には、Rustによる高性能バックエンドとWhisper/Parakeetという最新の音声認識モデル、さらにOllamaを用いたローカルLLM要約という組み合わせが、GPU非搭載環境でも実用的な速度で動作する点が評価されていると見られる。特に「4倍速」を謳う高速文字起こしと、企業のGDPR対応やコンプライアンス要件に直接応える設計思想が、他の類似ツールとの差別化要因になっている。

また、MITライセンスで無料のコミュニティ版を提供しつつ、より高度な機能を持つ有料PRO版を用意するというオープンコア型のビジネスモデルも、開発の持続可能性をアピールしつつ広く採用を促す戦略として機能しており、SNSやHacker News等での話題化がスター急増につながった可能性がある。

---
## 関連リンク

- https://github.com/Zackriya-Solutions/meetily
- https://meetily.ai

---
## メモ
