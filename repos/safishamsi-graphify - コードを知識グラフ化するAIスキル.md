---
url: https://github.com/safishamsi/graphify
saved: 2026-07-03
tags:
  - python
  - trending
  - tree-sitter
  - skills
  - gemini
  - knowledge-graph
  - leiden
  - codex
  - rag
  - graphrag
  - antigravity
  - claude-code
  - openclaw
category: GitHub Trending
status: 未読
rating:
---

# safishamsi/graphify

▎ コードを知識グラフ化するAIスキル

ライセンス: MIT
言語: Python
スター数: ⭐ 76,900 (+937 今日)
トレンド順位: #13 (2026-07-03)

---
## 概要

graphifyは、Claude Code・Codex・OpenCode・Cursor・Gemini CLIなど主要なAIコーディングエージェント向けの「スキル」として動作するツールで、コードやSQLスキーマ、Rスクリプト、シェルスクリプト、ドキュメント、論文、画像、動画といった雑多なファイル群を、問い合わせ可能な「知識グラフ」に変換する。Claude Codeであれば`/graphify`と入力するだけでフォルダ内のファイルを解析し、構造をグラフとして可視化・永続化してくれる。完全なマルチモーダル対応が特徴で、Claude Visionを用いてスクリーンショットや手書きの図、他言語の画像からも概念と関係性を抽出しグラフに統合できる。研究者や開発者がメモや論文、スクリーンショットを溜め込む「散らかったraw folder」問題(Andrej Karpathy氏の例が引用されている)を解決するために作られており、生のファイルを毎回読み込むのに比べてクエリあたりのトークン消費を71.5倍削減できるとうたう。生成したグラフはHTML、Obsidianボルト、Wikipedia風記事、JSONなど複数形式で出力され、セッションをまたいで再利用可能。対象ユーザーはAIエージェントに大量のコンテキストを効率的に読み込ませたい開発者やナレッジワーカーである。

---
## 主な機能・特徴

- AIエージェント向けスキル — Claude Code/Codex/Cursor/Gemini CLI等から`/graphify`で起動
- フルマルチモーダル対応 — コード・PDF・画像・手書き図まで解析対象
- 知識グラフ生成 — 概念と関係性を抽出し永続的なグラフとして保存
- トークン削減 — 生ファイル読み込みと比較し71.5倍少ないトークンでクエリ可能
- 複数フォーマット出力 — 対話的HTML、Obsidianボルト、Wiki記事、JSON
- 差分キャッシュ — SHA256キャッシュにより変更ファイルのみ再処理
- コミュニティ検出 — Leidenアルゴリズムでグラフのクラスタを可視化
- GRAPH_REPORT生成 — 「god node」や意外な関連性、次に聞くべき質問を提示

---
## トレンド入り理由の推測

graphifyは今日だけで+937スターと非常に大きな伸びを示しており、既存の総スター数(7万件超)と合わせて見ると、AIコーディングエージェント界隈で急速に話題化している最中のリポジトリだと考えられる。背景には「AIエージェントに大量のコンテキストをどう食べさせるか」という課題があり、Claude CodeのSkills機能やCodex、Gemini CLI、さらに名称から見て非常に新しいツールである「antigravity」など最新のエージェント環境にも対応している点が、早期採用者の間で強く共有された可能性が高い。

Andrej Karpathy氏の`/raw`フォルダ運用エピソードを引用した比喩がSNSで拡散されやすい分かりやすいストーリーになっていることも、バイラルな伸びの一因と推測される。また「知識グラフ×RAG×マルチモーダル」という組み合わせは、生成AI活用の高度化に伴い開発者の関心が集中しているテーマであり、Claude Code Skillsエコシステムの拡大とタイミングが重なったことで、一気にトレンド上位へ押し上げられたと考えられる。

---
## 関連リンク

- https://github.com/safishamsi/graphify
- https://graphifylabs.ai/

---
## メモ
