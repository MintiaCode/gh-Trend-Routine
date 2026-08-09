---
url: https://github.com/vitali87/code-graph-rag
saved: 2026-08-09
tags:
  - python
  - trending
  - ai
  - ast
  - claude-code
  - code-analysis
  - code-understanding
  - codebase-search
  - developer-tools
  - graph-database
  - knowledge-graph
  - llm
  - mcp
  - mcp-server
  - memgraph
  - monorepo
  - multi-language
  - python
  - rag
  - retrieval-augmented-generation
  - semantic-search
  - tree-sitter
category: GitHub Trending
status: 未読
rating:
---

# vitali87/code-graph-rag

▎ AIでモノレポを解析するRAG基盤

ライセンス: MIT
言語: Python
スター数: ⭐ 2900 (+59 今日)
トレンド順位: #2 (2026-08-09)

---
## 概要

Code-Graph-RAGは、複数言語が混在する大規模モノレポを対象に、Tree-sitterでソースコードを解析してMemgraph上にナレッジグラフを構築し、自然言語でコードベースを問い合わせ・編集できるようにするツールです。従来のテキストベースやベクトル検索中心のRAGでは捉えにくい、関数・クラス・モジュール間の呼び出し関係やインポート関係を構造化して保持することで、単なるキーワード一致ではなく「実際のコード構造に基づいた」検索と回答を可能にしています。ユーザーは自然言語の質問をCypherクエリに変換させてグラフを検索し、該当するコードの実体を取得したり、AST単位での安全なパッチ編集や、呼び出しグラフをたどったデッドコード検出、ast-grepによる構造的な検索・置換も行えます。Python、TypeScript、Rust、Go、Java、C/C++、C#、PHP、Lua、Dartなど多数の言語に対応し、MCPサーバーとしても動作するためClaude CodeなどのAIコーディングエージェントから直接利用できます。対象ユーザーは、大規模で言語混在なコードベースを保守する開発チームや、AIエージェントにコードベース理解を組み込みたい開発者です。

---
## 主な機能・特徴

- ナレッジグラフ構築 — Tree-sitterでコードを解析しMemgraphに関数・クラス・モジュールの関係を格納
- 自然言語クエリ — 質問をCypherクエリに自動変換してグラフを検索
- AIによる構造編集 — AST単位の差分プレビュー付きで安全にコードを書き換え
- デッドコード検出 — 呼び出し・参照エッジをエントリーポイントからたどって未使用コードを発見
- 構造的検索・置換 — ast-grepによるASTパターンベースの検索とリライトをエージェントツールとして提供
- データフロー追跡 — 代入・関数呼び出し・I/Oシンクを追う`FLOWS_TO`タイントエッジ(C#, Java, C, Go対応)
- MCPサーバー対応 — Claude Codeなど他のMCPクライアントから直接コードベースを操作可能
- 多言語対応 — Python, TypeScript, Rust, Go, Javaなど12言語以上をフルサポート

---
## トレンド入り理由の推測

Code-Graph-RAGは本日59スターと総スター数(約2,900)に対しては緩やかな伸びですが、AIエージェントによるコード理解・編集という今まさに注目度の高い領域に位置しており、継続的に開発者コミュニティから関心を集めていると考えられます。特に「Latest News」セクションで示されているRubyサポートの追加やast-grepによる構造的検索・置換機能、C#/Java/C/Goにまたがるデータフロー(タイント)追跡といった機能が最近立て続けに追加されており、活発な開発が継続していることがトレンド入りの一因と見られます。

MCPサーバーとして動作しClaude Codeなど主要なAIコーディングエージェントと直接統合できる点も大きな要因です。単純なベクトル検索RAGではなく、AST・グラフ構造に基づいた「正確なコード理解」を志向するアプローチは、AIエージェントに大規模モノレポを扱わせる際の精度向上ニーズと合致しており、AIコーディングエージェント関連ツールへの注目の高まりの中で継続的に発見・共有されているものと推測されます。

---
## 関連リンク

- https://github.com/vitali87/code-graph-rag
- https://code-graph-rag.com

---
## メモ
