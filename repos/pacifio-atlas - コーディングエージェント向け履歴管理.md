---
url: https://github.com/pacifio/atlas
saved: 2026-09-02
tags:
  - rust
  - trending
  - ai
  - ai-coding-assistant
  - claude-code
  - codex
  - coding-agents
  - git
  - gitops
  - kilo-code
  - mcp
  - mcp-client
  - opencode
  - opencode-ai
  - opencode-skills
  - self-hosted
  - skills
category: GitHub Trending
status: 未読
rating:
---

# pacifio/atlas

▎ コーディングエージェント向け履歴管理

ライセンス: MIT
言語: Rust
スター数: ⭐ 2806 (+895 今日)
トレンド順位: #9 (2026-09-02)

---
## 概要

Atlasは、AIコーディングエージェント専用のバージョン管理システムです。Claude CodeやCodexなど複数のAIエージェントがコードの大部分を生成する時代において、各セッションが判断の経緯を記憶せず、エージェントを切り替えるたびに文脈が失われ、数か月後になぜそのコード変更がされたのかを追跡できないという課題を解決します。Atlasは複数のエージェントをAgent Client Protocol(ACP)経由でラップし、オンデバイスのセマンティックメモリでコンテキストを強化しながら、セッションの全記録(プロンプト・ツール呼び出し・推論・ファイル変更)をコミットに紐づけて「チェックポイント」として保存します。ローカルモデルによる埋め込み生成、SQLiteでのセッション永続化、rebaseやamend後もpatch-id照合でリンクを維持する仕組みを備え、対象ユーザーは複数のAIエージェントを併用する開発チームや、自動変更の監査証跡を必要とするチームです。

---
## 主な機能・特徴

- Claude Code・Codex・独自Rustエージェント(Cerseiフレームワーク)を統一パイプラインで実行
- セッション全記録をコミットに紐づけるチェックポイント機構
- オンデバイス埋め込みによるセマンティック検索・過去の意思決定の参照
- Git履歴の書き換え(rebase/amend)後もpatch-id照合でリンクを維持
- バックリンク付きMarkdownのナレッジベース
- 複数タブでのマルチエージェント並行実行と共有メモリ
- 実コミットグラフによるGit可視化とファイル単位差分表示
- 組織機能によるクロスデバイス・チーム同期(任意)

---
## トレンド入り理由の推測

Atlasは総スター2,806に対し本日+895と非常に急激なスパイクを見せており、明確なバズが発生しています。AIコーディングエージェントの利用が日常化する中で「エージェントが何を、なぜ変更したのか分からない」という実務上の痛みは多くの開発者が共感しやすい課題であり、Claude CodeやCodexといった話題のツールと直接統合する点が強い訴求力を持ったと考えられます。

Rust製で高速に動作し、MCPクライアントやOpenCode/Kilo Codeなど複数のエージェントエコシステムをサポートしている点も、マルチエージェント運用が広がる現在のトレンドと合致しています。SNSやHacker News等での紹介をきっかけに一気に注目を集めた可能性が高く、AIエージェント関連ツール全体への関心の高まりを象徴する事例と言えます。

---
## 関連リンク

- https://github.com/pacifio/atlas
- https://www.tryatlas.cc/

---
## メモ
