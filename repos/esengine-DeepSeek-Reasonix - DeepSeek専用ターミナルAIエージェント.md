---
url: https://github.com/esengine/DeepSeek-Reasonix
saved: 2026-08-02
tags:
  - go
  - trending
  - agent
  - agent-framework
  - ai-agent
  - ai-coding
  - cli
  - coding-agent
  - deepseek
  - developer-tools
  - ink
  - llm
  - prompt-caching
  - r1
  - terminal
  - tool-use
  - tui
  - typescript
category: GitHub Trending
status: 未読
rating:
---

# esengine/DeepSeek-Reasonix

▎ DeepSeek専用ターミナルAIエージェント

ライセンス: MIT
言語: Go
スター数: ⭐ 29000 (+389 今日)
トレンド順位: #15 (2026-08-02)

---
## 概要

Reasonix(DeepSeek-Reasonix)は、DeepSeekモデルに最適化されたターミナル向けAIコーディングエージェントです。設定駆動・プラグイン駆動のアーキテクチャを採用し、単一の静的Goバイナリとして配布されることでインストールが容易な点が特徴です。最大の特徴はDeepSeekの「プレフィックスキャッシュ」の安定性を重視した設計で、長時間セッションを維持してもトークンコストを抑えられるよう調整されています。reasonix.tomlという設定ファイルでプロバイダー・使用ツール・プラグインをすべて宣言的に管理でき、DeepSeekをプリセットとして使いつつ、他のOpenAI互換エンドポイントも設定変更のみで利用可能です。外部ツールはMCP互換のstdio JSON-RPCサブプロセスとして動作するプラグイン形式で拡張でき、CLI/TUIに加えデスクトップアプリやVS Code拡張も同一のローカルエンジンを利用します。長時間動かしっぱなしで使う開発者や、トークンコストを抑えつつAIエージェントに継続的にコーディングを任せたいユーザーを主なターゲットにしています。

---
## 主な機能・特徴

- プレフィックスキャッシュ最適化 — DeepSeekのキャッシュ機構を活かしトークンコストを抑制
- 設定駆動アーキテクチャ — reasonix.tomlでプロバイダー・ツール・プラグインを宣言的管理
- マルチモデル対応 — DeepSeek以外のOpenAI互換エンドポイントも設定のみで追加可能
- プラグインシステム — MCP互換のstdio JSON-RPCで外部ツールを拡張
- 単一静的バイナリ — CGO無効化でクロスコンパイルが容易、npm/Homebrewで配布
- マルチクライアント — CLI/TUI・デスクトップアプリ・VS Code拡張が同一エンジンを共有
- コンテキストエンジン — 環境要約の注入や不要ツール出力の刈り込みでキャッシュ安定性を維持
- デュアルモデル運用 — 実行役とプランナー役を分離した2モデル並行実行にも対応

---
## トレンド入り理由の推測

本日+389スター、累計約2.9万スターという急上昇は、Claude CodeやCodex CLIに続く「ターミナル常駐型AIコーディングエージェント」というカテゴリ自体が現在非常に注目されていることが背景にあります。中でもDeepSeekはコスト効率の高いモデルとして人気が高く、そのAPI特性(プレフィックスキャッシュ)に最適化した専用エージェントというポジショニングが、コストを抑えて長時間エージェントを走らせたい開発者層に強く刺さったと考えられます。

さらにCLI/TUIだけでなくデスクトップアプリやVS Code拡張まで用意され、npmやHomebrewでのワンコマンド導入、SignPathによるコード署名済みWindowsインストーラーなど配布面の完成度が高いことも急速な採用を後押ししています。GoによるシングルバイナリでCGO依存もないため導入障壁が低く、既にAIコーディングエージェントに慣れたユーザー層への横展開が進みやすいことも、短期間でのスター急増につながったとみられます。

---
## 関連リンク

- https://github.com/esengine/DeepSeek-Reasonix
- https://reasonix.io/

---
## メモ
