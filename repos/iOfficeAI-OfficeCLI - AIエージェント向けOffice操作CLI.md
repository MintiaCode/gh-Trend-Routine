---
url: https://github.com/iOfficeAI/OfficeCLI
saved: 2026-07-07
tags:
  - c#
  - trending
  - agent
  - cli
  - ai
  - skills
  - presentation
  - excel
  - word
  - xlsx
  - office
  - docx
  - pptx
  - codex
  - claude-code
category: GitHub Trending
status: 未読
rating:
---

# iOfficeAI/OfficeCLI

▎ AIエージェント向けOffice操作CLI

ライセンス: Apache-2.0
言語: C#
スター数: ⭐ 9700 (+802 今日)
トレンド順位: #9 (2026-07-07)

---
## 概要

OfficeCLIは、AIエージェントがMicrosoft Office(Word・Excel・PowerPoint)のファイルをOffice本体を一切インストールせずに読み書き・自動化できるようにする、単一バイナリのCLIツールである。.NETランタイムを内包したセルフコンテインドな実行ファイルとして配布され、シェルスクリプト・PowerShell・Homebrew・npmなど複数の方法で導入可能。最大の特徴は、生のXMLをAIに解釈させるのではなく、ドキュメントをHTML/PNG/スクリーンショットとして描画するレンダリングエンジンを内蔵し、AIエージェントが「見て」内容を確認できるようにしている点にある。CLIコマンドとJSON出力による構造化されたインターフェースを軸に、常駐モードでの対話的な複数手順操作や、バッチ処理による一括変更にも対応する。MCP(Model Context Protocol)サーバーを標準搭載し、Claude Code・Cursor・VS Codeなど主要なAIコーディングツールと直接連携できるほか、対応環境へのスキルファイル自動インストール機能も備える。レポート自動生成やCI/CDパイプラインへの組み込み、テンプレートへのデータ流し込みなど、Officeドキュメントを扱うワークフローをAIエージェントに任せたい開発者・企業を主なターゲットとする。

---
## 主な機能・特徴

- Office不要の単一バイナリ — .NETランタイム内蔵でOfficeインストールなしにdocx/xlsx/pptxを操作
- ビジュアルレンダリング — ドキュメントをHTML/PNG化しAIが視覚的に内容を確認可能
- 数式・ピボットエンジン — 350以上のExcel関数を自動評価、動的配列やOOXMLネイティブピボットにも対応
- テンプレートマージ — `{{key}}`形式のプレースホルダーを全フォーマット横断でJSONデータに置換
- ラウンドトリップ変換 — `dump`でドキュメントを再生可能なバッチJSON化、`batch`で再生
- パスベース操作 — `/slide[1]/shape[2]`のような安定したパスでXML名前空間を意識せず要素を指定
- 3層アーキテクチャ — セマンティック読み取り(L1)からDOM操作(L2)、生XMLアクセス(L3)まで段階的に対応
- MCPサーバー内蔵 — Claude Code/Cursor/VS Code等へ直接統合、スキルファイル自動配置
- ライブプレビュー — `watch`コマンドでブラウザ上のリアルタイムプレビューと自動更新を提供

---
## トレンド入り理由の推測

本日の獲得スター数802は累計約9,700の8%強に相当し、明確な急上昇を示している。トピックタグに「agent」「cli」「codex」「claude-code」「mcp」的な要素が並んでいることからも分かる通り、AIコーディングエージェントがOfficeファイルを直接操作したいという需要にピンポイントで応える設計になっており、AIエージェント向けツール群(Skills、MCPサーバー)が急速に整備されている現在の潮流に完全に乗っている。直近のリリース(v1.0.129、7月6日付)が示すように開発が非常に活発で、頻繁なアップデートが継続的な話題化とスター獲得を後押ししていると考えられる。

技術的には「AIにXMLを読ませる」のではなく「AIに画面を見せる」という視覚的レンダリングのアプローチが目新しく、LLMのマルチモーダル能力を活用した実用的なユースケースとして注目を集めやすい。Word/Excel/PowerPoint全てを単一ツールでカバーし、しかもOffice本体不要という導入障壁の低さも、CI/CDや自動化パイプラインへの組み込みを検討する開発者に強く刺さっている要因だろう。

---
## 関連リンク

- https://github.com/iOfficeAI/OfficeCLI
- https://officecli.ai

---
## メモ

