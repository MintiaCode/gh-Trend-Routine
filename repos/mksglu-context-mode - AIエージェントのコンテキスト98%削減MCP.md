---
url: https://github.com/mksglu/context-mode
saved: 2026-05-05
tags:
  - typescript
  - trending
  - antigravity
  - claude
  - claude-code
  - claude-code-hooks
  - claude-code-plugins
  - claude-code-skill
  - codex
  - codex-cli
  - context-mode
  - copilot
  - cursor-plugin
  - kiro
  - mcp
  - mcp-server
  - mcp-tools
  - openclaw
  - opencode
  - pi-agent
  - skills
  - zed-extension
category: GitHub Trending
status: 未読
rating:
---

# mksglu/context-mode

▎ AIエージェントのコンテキスト98%削減MCP

ライセンス: NOASSERTION
言語: TypeScript
スター数: ⭐ 12939 (+344 今日)
トレンド順位: #6 (2026-05-05)

---
## 概要

Context ModeはAIコーディングエージェントのコンテキストウィンドウを最適化するMCPサーバーです。MCPツール呼び出しの生データをサンドボックス化してコンテキストウィンドウへの流入を防ぎ、最大98%のコンテキスト使用量削減を実現します。セッション継続性のためにSQLiteとBM25全文検索で操作履歴を追跡し、会話コンパクション後も作業状態を復元できます。さらに「コードで考える」パラダイムを採用し、LLMをデータプロセッサではなくコードジェネレーターとして扱うことで、47回のRead呼び出しを1回のスクリプト実行に置き換えます。出力圧縮機能でフィラーや丁寧表現を排除し、出力トークンを65〜75%削減します。Claude Code、Cursor、Codex CLI、GitHub Copilot、Kiro、Zedなど14のプラットフォームに対応しており、Microsoft・Google・Meta等の大企業チームでも採用されています。

---
## 主な機能・特徴

- コンテキストサンドボックス — ツール出力を隔離して315KBを5.4KBに圧縮、98%削減を達成
- セッション継続性 — SQLite+FTS5でファイル編集・gitオペレーション・タスクを追跡し、会話コンパクション後も作業状態を復元
- コードで考えるパラダイム — LLMをデータプロセッサでなくコードジェネレーターとして扱い、多数のツール呼び出しを1スクリプトに置き換え
- 出力圧縮 — フィラー・丁寧表現・冗長説明を排除し、出力トークンを65〜75%削減
- 14プラットフォーム対応 — Claude Code、Cursor、Codex CLI、GitHub Copilot、Kiro、Zed他に広く対応
- BM25セマンティック検索 — セッション履歴をFTS5でインデックス化し、関連情報のみを効率的に取得
- MCPサーバー形式 — 標準MCPプロトコルで既存ワークフローへ容易に統合可能

---
## トレンド入り理由の推測

本日（2026-05-05）のpushed_atがまさに当日と一致しており、大型アップデートまたは重要な新機能がリリースされた可能性が高いです。+344スターの急増は、Claude Code、Cursor、GitHub Copilotなど複数の主要AIコーディングツールコミュニティ内で同時に話題となったことを示しています。Hacker Newsで570+ポイントを獲得した実績もあり、技術系コミュニティでの認知度が非常に高いプロジェクトです。

AIコーディングエージェントの普及に伴い、コンテキストウィンドウの枯渇は開発者が共通して直面する課題となっています。そのペインポイントに対して98%削減という具体的な数字で解決策を示すアプローチが強い説得力を持っています。Claude Code、Codex CLI、Cursorなど現在最も注目されているAIコーディングツールすべてに対応しているため、広いユーザーベースにアピールしています。

総スター数12,939という大きな実績を持ちながら本日もアクティブに開発が続いている点が信頼性を高めています。Microsoft・Google・Meta・NVIDIAなど大手企業チームでの採用実績を掲げており、エンタープライズユーザーへの訴求力も高いことが継続的な注目を集める理由となっています。

---
## 関連リンク

- https://github.com/mksglu/context-mode
- https://context-mode.com

---
## メモ
