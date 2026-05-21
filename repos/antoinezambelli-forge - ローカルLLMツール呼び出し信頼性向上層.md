---
url: https://github.com/antoinezambelli/forge
saved: 2026-05-21
tags:
  - python
  - trending
  - self-hosted
  - agents
  - llm
  - llama-cpp
  - function-calling
  - ollama
  - llamafile
  - agentic-workflow
  - agentic-ai
  - tool-calling
category: GitHub Trending
status: 未読
rating:
---

# antoinezambelli/forge

▎ ローカルLLMツール呼び出し信頼性向上層

ライセンス: MIT
言語: Python
スター数: ⭐ 1,400 (+449 今日)
トレンド順位: #12 (2026-05-21)

---
## 概要

forgeは、セルフホスト型（ローカル）LLMのツール呼び出し（tool-calling）の信頼性を大幅に向上させるPythonフレームワークです。8B程度の小規模ローカルモデルが多段階エージェントワークフローを高い成功率でこなせるよう、ガードレールとコンテキスト管理の仕組みを提供します。

主な解決策は3層構造です。①WorkflowRunner — ツール定義から実行ループ全体を管理する統合エージェント環境、②ガードレールミドルウェア — レスポンスの検証・不正なツール呼び出しの自動修正・必須ステップの強制実行、③プロキシサーバー — 任意のOpenAI互換クライアントとローカルモデルの間に透過的に挟んでガードレールを適用するドロップイン方式。OllamaやllLama-server、Llamafile、Anthropic APIをバックエンドとしてサポートし、Ministral-3 8B等の小型モデルで26シナリオ評価スイートにて86.5%のスコアを達成しています。

---
## 主な機能・特徴

- WorkflowRunner — ツール定義・システムプロンプト・実行ループを一括管理
- ガードレールミドルウェア — レスポンス検証・不正ツール呼び出しの自動修正
- StepEnforcer — 必須処理ステップの強制実行でワークフロー完了を保証
- VRAMアウェアコンテキスト管理 — GPU VRAM残量に応じたトークン予算制御
- TieredCompaction — 古いコンテキストを段階的に圧縮して長期タスクを継続
- プロキシサーバー — OpenAI互換クライアント向け透過型ガードレールプロキシ
- SlotWorker — 複数エージェントがGPUスロットを優先度付きキューで共有する機構
- 26シナリオ評価スイート — OG-18基本層 + 8シナリオ高度推論層によるベンチマーク

---
## トレンド入り理由の推測

ローカルLLMブームが続く中、ツール呼び出しの信頼性という現実的な課題への実践的解答としてforgeが急浮上しました。GPT-4oやClaudeといったフロンティアモデルはAPI経由でfunction callingを安定して実行できますが、OllamaやLlamafileで動かす8B程度のローカルモデルでは複数ステップのツール呼び出しが途中で失敗するケースが頻出します。forgeはその問題を論文（ACM DOI公開）と実装の両面で解決しており、「研究+コード」がセットになっているのが開発者に刺さっています。

本日449スターという急増は、HackerNewsやRedditのr/LocalLLaMAで取り上げられたことで一気に認知が拡散した典型的なバイラルパターンです。特に「Ministral-3 8B単体でワークフロー成功率86.5%」という具体的な数値ベンチマークが実用志向の開発者の心を掴み、共有が加速したと見られます。クラウドAPI依存を脱したいプライバシー重視のエンタープライズ開発者にとってforgeは直接的なソリューションとなり得るため、企業ユーザーからの流入も本日のスター急増に貢献していると推測されます。

---
## 関連リンク

- https://github.com/antoinezambelli/forge

---
## メモ
