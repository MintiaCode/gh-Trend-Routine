---
url: https://github.com/CoplayDev/unity-mcp
saved: 2026-07-04
tags:
  - c#
  - trending
  - gamedev
  - ai
  - unity
  - mcp
  - game-development
  - unity3d
  - gemini
  - openai
  - cursor
  - videogames
  - copilot
  - claude
  - llm
  - anthropic
  - ai-integration
  - model-context-protocol
category: GitHub Trending
status: 未読
rating:
---

# CoplayDev/unity-mcp

▎ AIでUnityエディタを操作するMCP

ライセンス: MIT
言語: C#
スター数: ⭐ 11500 (+68 今日)
トレンド順位: #16 (2026-07-04)

---
## 概要

Unity MCPは、Model Context Protocol(MCP)を用いてAIアシスタントとUnityエディタを橋渡しするオープンソースフレームワークである。Claude、Cursor、VS Code、Gemini CLI、ローカルLLMなど複数のMCP対応クライアントから、自然言語の指示だけでUnityエディタ上のシーン編集、アセット管理、スクリプト編集、テスト実行、ビルド自動化などを行えるようにする。従来、AIコーディングアシスタントはコード生成には強い一方、GUI操作が中心のゲームエンジンとの連携が乏しかったが、本プロジェクトは47種類のMCPツールエントリポイントを介してエディタ操作をAIに開放することでそのギャップを埋める。インディー開発者から大規模チームまで、AI活用によるゲーム開発ワークフローの高速化を目指す幅広いUnity開発者を対象とし、Unity 2021.3 LTS〜6.xおよびPython 3.10以上に対応する。プラットフォーム非依存のプロトコル設計により、特定AIベンダーへのロックインを避けつつ複数のクライアントを併用できる点も特徴である。

---
## 主な機能・特徴

- シーン・アセット管理 — 自然言語指示でゲームオブジェクトやシーンを作成・整理
- スクリプト編集 — Roslynによる検証を伴うC#コードの自動編集
- テスト・プロファイリング — 自動テスト実行とパフォーマンス分析
- ビルド自動化 — プロジェクトのビルドプロセスを簡略化
- 複数Unityインスタンス対応 — 複数プロジェクトを同時に管理
- ツールのドメイン別グルーピング — VFX、アニメーション、UI、テストなど機能別に整理
- マルチクライアント対応 — Claude Desktop、Cursor、VS Code、Windsurf、Cline、Gemini CLIなどで利用可能
- 47種類のMCPツールエントリポイントによる幅広い操作範囲

---
## トレンド入り理由の推測

本日68個という新規スター数自体は他のトレンド入りリポジトリと比べて控えめだが、累計1.15万スターという実績と合わせ、Unity開発におけるMCP採用の広がりを反映していると考えられる。近年、Model Context ProtocolがAnthropic発の標準として急速に業界標準化しつつあり、Claude・Cursor・Gemini CLIなど主要コーディングエージェントが軒並みMCP対応を進めていることが、ゲームエンジンとの統合ツールへの関心を継続的に押し上げている。

技術的には、GUI操作中心で自動化が難しかったUnityエディタを自然言語で操作できるようにする点が新規性が高く、ゲーム開発者コミュニティにおいて「AIエージェントにゲーム制作を手伝わせる」という近年のトレンドと合致している。Coplayという専業ベンダーによる継続的なメンテナンスと、47ツールという充実した機能セットも信頼性の高さを示し、企業チームでの採用を後押ししていると見られる。

また、生成AIとゲーム開発の融合が現在の主要な技術トレンドの一つであり、Unity公式ではないもののMCPエコシステムのデファクトスタンダード的地位を確立しつつあることが、日々安定したスター獲得につながっていると考えられる。

---
## 関連リンク

- https://github.com/CoplayDev/unity-mcp
- https://www.coplay.dev

---
## メモ
