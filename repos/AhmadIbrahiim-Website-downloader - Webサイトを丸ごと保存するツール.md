---
url: https://github.com/AhmadIbrahiim/Website-downloader
saved: 2026-07-07
tags:
  - html
  - trending
  - scraper
  - downloader
  - assets
  - offline-web-pages
category: GitHub Trending
status: 未読
rating:
---

# AhmadIbrahiim/Website-downloader

▎ Webサイトを丸ごと保存するツール

ライセンス: MIT
言語: HTML
スター数: ⭐ 3900 (+173 今日)
トレンド順位: #6 (2026-07-07)

---
## 概要

Website-downloaderは、任意のWebサイトのHTML・JavaScript・スタイルシート・画像などのアセットを含めて丸ごとダウンロードし、オフラインで閲覧可能な形にまとめてくれるNode.js製ツールである。内部ではLinuxの`wget`コマンドを`--mirror`・`--convert-links`・`--adjust-extension`・`--page-requisites`・`--no-parent`といったオプション付きで呼び出し、リンクを相対パスに変換しながらサイト構造をそのまま複製する。ダウンロードした一式は`archiver`ライブラリでZIPに圧縮され、WebSocket経由で進捗を通知しつつユーザーに配信される仕組みになっている。Webサイトのバックアップを取りたい開発者、既存サイトを解析・改修したいエンジニア、ネット接続のない環境でサイトを閲覧したいユーザーなどを主な対象とし、コマンドラインの知識がなくてもブラウザ上のフォームにURLを入力するだけで利用できる手軽さが特徴。Replit・Glitch・Railway・Render等へのワンクリックデプロイにも対応しており、自分専用のインスタンスをすぐに立ち上げられる。

---
## 主な機能・特徴

- サイト全体のミラーリング — wgetの`--mirror`オプションでページ・アセットを再帰的に取得
- オフライン対応リンク変換 — `--convert-links`で相対パスに変換しローカル閲覧を可能に
- アセット一括取得 — JavaScript・CSS・画像などページ表示に必要な要素をまとめて保存
- ZIP圧縮配信 — archiverライブラリでダウンロード結果を一つのZIPにまとめて提供
- リアルタイム進捗通知 — WebSocketでダウンロード状況をブラウザに逐次表示
- ワンクリックデプロイ対応 — Replit/Glitch/Railway/Cyclic/Koyeb/Renderへの即時デプロイボタンを用意
- シンプルなWeb UI — URLを入力するだけで使えるノーコードなインターフェース

---
## トレンド入り理由の推測

本日の獲得スター数173は累計約3,900に対して約4.4%と、爆発的というより着実な伸びである。リポジトリ自体は目新しい技術を使っているわけではなく、wgetラッパーというシンプルな仕組みだが、「任意のサイトを丸ごとオフライン保存したい」という普遍的なニーズに応え続けていることが、日々一定数の新規スターを集める理由と考えられる。SNSやニュースサイトでの再紹介、ブックマークサービスやアーカイブ文化への関心の高まりがきっかけになった可能性が高い。

技術的な目新しさよりも「手軽さ」が支持されている点も特徴的で、コマンドライン操作なしにブラウザから直接サイトをダウンロードできるUXと、複数のワンクリックデプロイ手段を用意している間口の広さが、開発者以外の層にもリーチしていると考えられる。生成AIやエージェント関連のリポジトリが上位を占める昨今のトレンドの中で、こうした地道で実用的なユーティリティが根強く支持されている点も興味深い。

---
## 関連リンク

- https://github.com/AhmadIbrahiim/Website-downloader
- https://website-downloader.onrender.com

---
## メモ

