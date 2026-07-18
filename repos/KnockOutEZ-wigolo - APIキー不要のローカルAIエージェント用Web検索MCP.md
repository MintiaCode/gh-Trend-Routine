---
url: https://github.com/KnockOutEZ/wigolo
saved: 2026-07-18
tags:
  - typescript
  - trending
  - nodejs
  - search
  - agent
  - cli
  - search-engine
  - privacy
  - typescript
  - ai
  - mcp
  - web-crawler
  - web-scraping
  - developer-tools
  - metasearch
  - claude
  - web-search
  - rag
  - local-first
  - ai-agent
  - model-context-protocol
  - mcp-server
category: GitHub Trending
status: 未読
rating:
---

# KnockOutEZ/wigolo

▎ APIキー不要のローカルAIエージェント用Web検索MCP

ライセンス: AGPL-3.0-only
言語: TypeScript
スター数: ⭐ 1100 (+192 今日)
トレンド順位: #9 (2026-07-18)

---
## 概要

wigoloは、AIコーディングエージェント向けにWeb検索・取得・クロール・抽出・キャッシュ・類似検索・リサーチ機能を一括提供するMCPサーバーです。Claude Code、Cursor、Codex、Gemini CLI、VS Code、Windsurf、Zedなど主要なコーディングエージェントに加え、LangChainやCrewAI、n8nなど任意のMCPクライアントやREST経由でも利用できます。既存のWeb検索連携はAPIキーの管理やクラウド利用料が課題になりがちですが、wigoloはブラウザエンジンやオンデバイスモデルをローカルにダウンロードして動作するローカルファースト設計により、APIキー不要・クラウド不要・クエリ課金ゼロを実現しています。`npx wigolo init`一発でエージェントへのMCP設定まで自動化される手軽さも特徴で、検索結果は出典位置に紐づいた抜粋と引用IDを持つ「根拠付きエビデンス」として返されるため、エージェントが正確な引用付き回答を生成しやすい設計になっています。要約や統合回答の生成にはLLMが必要なため、無料のGemini APIキーなどの利用が推奨されていますが、Ollama等で完全ローカル・キーレス運用も可能です。

---
## 主な機能・特徴

- 検索・取得・クロール・抽出・キャッシュ・類似検索を1つのMCPサーバーで提供
- APIキー不要・クラウド不要でコア機能が動作し、クエリ課金が発生しない
- Claude Code、Cursor、Codex、Gemini CLI等の主要エージェントにワンコマンドで統合
- 検索結果に出典箇所への正確な引用と信頼度スコアを付与するエビデンス指向設計
- `research`/`agent`モードはLLMを使い引用付きの統合回答を自動生成
- Gemini・OpenAI・Anthropic・Groq・Ollamaなど複数LLMプロバイダに対応
- npm・Docker・Homebrew・単一バイナリなど多様な配布チャネルをサポート
- ヘルスチェックコマンド`wigolo doctor`でセットアップ状態を即座に確認可能

---
## トレンド入り理由の推測

wigoloが本日大きく伸びた(スター192、フォーク81に対しスター1,100)最大の要因は、直近リリースのv0.2.0(2026年7月17日、すなわち昨日)によるものと見られます。MCP(Model Context Protocol)を軸にしたAIエージェント向けツールは、Claude CodeやCursorなど各種コーディングエージェントの普及に伴い急速に注目度が高まっている分野であり、そこに「APIキー不要・課金なし」という明確な差別化ポイントを持つツールが投入されたことがバズを呼んだと考えられます。

既存のWeb検索MCPの多くはBing/Google等の有料検索APIキーを前提としており、個人開発者やOSSコミュニティにとって導入障壁になっていました。wigoloはブラウザエンジンとオンデバイスモデルをローカルに持つことでこの障壁を取り除いており、「ローカルファーストAI」というトレンドとも合致します。トピックタグにmcp、rag、ai-agent、model-context-protocolが並んでいることからも、AIエージェントのツール連携(MCPエコシステム)拡大という業界トレンドの波に乗ったリリースであることがうかがえます。

さらに、Claude Code・Cursor・Zed・Antigravityなど話題性の高い複数のエージェントに対する即時対応を謳っている点も、各エージェントのユーザーコミュニティ経由での拡散を後押しし、リリース直後の急激なスター増加につながった可能性が高いです。

---
## 関連リンク

- https://github.com/KnockOutEZ/wigolo
- https://knockoutez.github.io/wigolo/

---
## メモ
