---
url: https://github.com/1jehuang/jcode
saved: 2026-04-29
tags:
  - rust
  - trending
  - ai
  - claude
  - cli
  - coding-agent
  - llm
  - mcp
  - openai
  - rust
  - terminal
  - tui
category: GitHub Trending
status: 未読
rating:
---

# 1jehuang/jcode

▎ 高性能Rustコーディングエージェント環境

ライセンス: MIT
言語: Rust
スター数: ⭐ 1305 (+386 今日)
トレンド順位: #5 (2026-04-29)

---
## 概要

jcodeは、次世代のコーディングエージェントハーネスとして設計されたRust製ツールです。マルチセッションワークフロー・無限のカスタマイズ性・高いパフォーマンスを目指して構築されており、Claude Code・Codex CLI・GitHub Copilot CLIなど既存のAIコーディングツールと比較して圧倒的に低いメモリ消費量を実現しています。1セッションの場合わずか27.8MB（組み込みオフ時）から、10セッション並行でも117.0MBという省メモリ設計が特徴です。MCP（Model Context Protocol）対応、OpenAIとClaudeの両プロバイダーをサポートし、TUIインターフェースで使いやすく設計されています。Linux・macOS・Windows対応で、ワンコマンドインストールが可能です。

---
## 主な機能・特徴

- 超低メモリ消費 — 1セッションあたり最小27.8MB、Claude Code（386MB）の1/14以下のRAM使用
- マルチセッション対応 — 10並行セッションでも260MBに抑えた高効率なアーキテクチャ
- マルチプロバイダー — Claude（Anthropic）とOpenAIの両LLMプロバイダーに対応
- MCP対応 — Model Context Protocolをサポートし、拡張ツールとの連携が可能
- TUIインターフェース — ターミナル上で動作する視覚的に使いやすいUI
- ローカル埋め込み対応 — ローカル埋め込みモデルを使ったコンテキスト検索機能
- クロスプラットフォーム — Linux・macOS・Windowsに対応したマルチプラットフォーム設計

---
## トレンド入り理由の推測

jcodeは、AIコーディングエージェントの「メモリ・パフォーマンス問題」というペインポイントを直撃したことでトレンド入りしました。Claude Code・Codex CLI・GitHub Copilot CLIなどの主要ツールのRAM使用量を詳細なベンチマークで比較し、圧倒的な省メモリを証明したことが開発者の注目を集めました。本日+386スターという数字は、Rust製の高性能ツールへの関心の高さを反映しています。

pushed_atが2026-04-29T20:53:57Zと当日の夕方に更新されており、新バージョンのリリースや改善がトレンド入りのきっかけになった可能性があります。AIコーディングエージェントが乱立する市場において、「スキルシーリングを上げる（raise the skill ceiling）」というコンセプトは、プロの開発者向けの高度なユースケースに訴求しています。

Rustで実装されていることで信頼性と速度を担保しつつ、MCP対応によって既存のツールチェーンとの相互運用性も確保しています。AIコーディングツール比較記事やベンチマーク動画でのシェアが急増したことで、一気にGitHubトレンドに浮上したと推測されます。

---
## 関連リンク

- https://github.com/1jehuang/jcode

---
## メモ

