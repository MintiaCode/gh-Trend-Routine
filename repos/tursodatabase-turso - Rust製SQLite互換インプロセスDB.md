---
url: https://github.com/tursodatabase/turso
saved: 2026-06-20
tags:
  - rust
  - trending
  - sql
  - database
  - webassembly
  - sqlite3
  - embedded-database
category: GitHub Trending
status: 未読
rating:
---

# tursodatabase/turso

▎ Rust製SQLite互換インプロセスDB

ライセンス: MIT
言語: Rust
スター数: ⭐ 20200 (+774 今日)
トレンド順位: #4 (2026-06-20)

---
## 概要

TursoはRustで書かれたインプロセスSQLデータベースで、SQLiteとの完全な互換性を持つ。SQLiteのSQL方言とファイルフォーマットをそのまま使用できるため、既存のSQLiteベースのアプリケーションからの移行が容易である。従来のSQLiteが抱えていた書き込みスループットの制約をBEGIN CONCURRENTによるMVCC（多版同時実行制御）で解消し、リアルタイムのデータ変更追跡（CDC）にも対応する。Go、JavaScript、Python、Rust、Java、.NETなど主要言語のバインディングを提供し、WebAssemblyを通じてブラウザ上でも動作する。Linuxではio_uringによる非同期I/Oをサポートし、ベクトル検索やtantivy駆動の全文検索といった先進的な機能も実験的に搭載している。組み込みデータベースとして軽量かつ高性能を求める開発者、特にエッジコンピューティングやサーバーレス環境でSQLiteの上位互換を必要とするエンジニアに最適なソリューションである。

---
## 主な機能・特徴

- SQLite完全互換 — SQL方言・ファイルフォーマットをそのまま継承し移行コストゼロ
- BEGIN CONCURRENT — MVCCベースの並行書き込みで書き込みスループットを大幅向上
- Change Data Capture — データベース変更をリアルタイムに追跡・配信
- マルチ言語バインディング — Go・JavaScript・Python・Rust・Java・.NETに対応
- WebAssembly対応 — ブラウザ上でもSQLデータベースを直接実行可能
- io_uring非同期I/O — Linux環境での高性能I/O処理を実現
- ベクトル検索・全文検索 — tantivy駆動の全文検索とベクトル類似検索を実験搭載
- MCPサーバーモード — AIアシスタントからデータベースを直接操作するインターフェース

---
## トレンド入り理由の推測

Tursoが本日774スターを獲得しトレンド入りした背景には、SQLiteの急速な再評価とRustエコシステムの成熟がある。近年、エッジコンピューティングやサーバーレスアーキテクチャの普及に伴い、軽量でインプロセス動作するデータベースへの需要が急増している。TursoはSQLiteの互換性を維持しつつ、従来の弱点であった並行書き込み性能を克服しており、この組み合わせが開発者の強い関心を集めている。

また、2026年5月のv0.6.1リリースで安定性が向上し、MCPサーバーモードの搭載によりAIエージェントとの統合が容易になった点も注目を集めた要因と考えられる。AIエージェントがローカルデータベースを直接操作するユースケースは今まさにホットなトピックであり、Tursoの組み込み型アーキテクチャはこのトレンドに完璧にマッチしている。

さらに、WebAssembly対応によりブラウザ上でSQLデータベースを動作させるという革新的なアプローチが、フロントエンド開発者やフルスタック開発者層にも訴求力を持っている。Rustの高い安全性とパフォーマンスを武器に、SQLiteの次世代版として業界の注目を一身に集めている。

---
## 関連リンク

- https://github.com/tursodatabase/turso
- https://turso.tech

---
## メモ
