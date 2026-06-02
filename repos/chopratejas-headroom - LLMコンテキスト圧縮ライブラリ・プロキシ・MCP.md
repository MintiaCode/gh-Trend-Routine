---
url: https://github.com/chopratejas/headroom
saved: 2026-06-02
tags:
  - python
  - trending
  - agent
  - ai
  - anthropic
  - claude-code
  - compression
  - context-engineering
  - context-window
  - cursor
  - fastapi
  - langchain
  - llm
  - mcp
  - openai
  - prompt-engineering
  - proxy
  - rag
  - token-optimization
  - tokens
  - typescript
category: GitHub Trending
status: 未読
rating:
---

# chopratejas/headroom

▎ LLMコンテキスト圧縮ライブラリ・プロキシ・MCP

ライセンス: Apache-2.0
言語: Python
スター数: ⭐ 5,932 (+1266 今日)
トレンド順位: #1 (2026-06-02)

---
## 概要

HeadroomはAIエージェントがLLMに送信するコンテンツ（ツール出力、ログ、RAGチャンク、ファイル、会話履歴）をLLMに届く前に圧縮するコンテキスト圧縮レイヤーです。60〜95%のトークン削減を実現しながら、回答品質は維持されます。ライブラリ・プロキシ・MCPサーバーの3形態で提供され、あらゆるAIエージェント環境に統合可能です。Claude Code、Cursor、Codex、Aiderなど主要エージェントと互換性があり、データはローカルに保持されます。6種類の圧縮アルゴリズム（SmartCrusher、CodeCompressor、Kompress-baseモデル等）を搭載し、コンテンツタイプに応じて最適なアルゴリズムを自動選択するContentRouterを備えています。圧縮後も元データはCCR（Contextual Compression with Retrieval）として保持され、LLMが必要時に取得できる可逆的な設計が特徴です。

---
## 主な機能・特徴

- ライブラリモード — `compress(messages)` をPython/TypeScriptで呼び出してインライン圧縮
- プロキシモード — `headroom proxy --port 8787` でコード変更ゼロのドロップイン対応
- エージェントラップ — `headroom wrap claude|codex|cursor|aider|copilot` 一発起動
- MCPサーバー — `headroom_compress`、`headroom_retrieve`、`headroom_stats` ツール提供
- クロスエージェントメモリ — Claude・Codex・Gemini間で共有、自動重複排除
- `headroom learn` — 失敗セッションを学習しCLAUDE.md/AGENTS.mdへ修正を書き込み
- CacheAligner — プロバイダーのKVキャッシュを最大活用するプレフィックス安定化

---
## トレンド入り理由の推測

本日+1,266スターという急激な増加は、コンテキストウィンドウの限界問題がAIエンジニアリング界隈で最も熱い課題となっている中でのタイムリーなリリースによるものです。Claude CodeやCursor、Codex CLIなどのAIコーディングエージェントが急速に普及し、大規模コードベースを扱う際のトークンコスト問題が顕在化している今、60〜95%削減という具体的な数字を示したソリューションは強い訴求力を持ちます。

pushed_atが2026-06-02と本日であることから、新機能のリリースや大幅なアップデートが行われた可能性が高く、それがHacker NewsやRedditのAIエンジニアリングコミュニティへの拡散トリガーになったと考えられます。Kompress-baseという独自のHugging Faceモデルを内包し、JSONにはSmartCrusher、コードにはAST解析のCodeCompressorを使い分けるアーキテクチャの技術的独自性も注目を集めた要因でしょう。

また、Claude Code・Cursor・Codexなど複数のエージェントに対応し、既存のOpenAI互換クライアントであれば設定変更不要で利用できる設計は実用性の高さをアピールしており、AIエージェント活用コストの削減という現実的なビジネス課題を解決するツールとして広く共感を得ています。

---
## 関連リンク

- https://github.com/chopratejas/headroom
- https://headroom-docs.vercel.app/docs

---
## メモ
