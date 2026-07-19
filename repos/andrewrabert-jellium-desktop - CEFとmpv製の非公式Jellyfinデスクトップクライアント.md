---
url: https://github.com/andrewrabert/jellium-desktop
saved: 2026-07-19
tags:
  - rust
  - trending
category: GitHub Trending
status: 未読
rating:
---

# andrewrabert/jellium-desktop

▎ CEFとmpv製の非公式Jellyfinデスクトップクライアント

ライセンス: GPL-2.0
言語: Rust
スター数: ⭐ 1300 (+54 今日)
トレンド順位: #6 (2026-07-19)

---
## 概要

Jellium Desktopは、オープンソースのメディアサーバーであるJellyfin向けの非公式デスクトップクライアントです。ブラウザ経由でのアクセスに頼らず、専用アプリからメディアをストリーミングできることを目指して開発されています。UI描画にはChromium Embedded Framework(CEF)を、動画再生には高性能な再生エンジンmpvを組み合わせるアーキテクチャを採用しており、Webレンダリングの柔軟性とネイティブ動画再生のパフォーマンスを両立させています。Linux・macOS・Windowsのマルチプラットフォームに対応し、x86_64・ARM64・Apple Siliconなど複数のアーキテクチャ向けにビルドが提供されます。AppImageやFlatpakなど多様な配布形式を用意し、コマンドラインからmpvオプションを直接指定できるなど、上級ユーザー向けの柔軟性も備えています。Jellyfinサーバーの管理者や、ブラウザではなく専用アプリでメディアを楽しみたいユーザーを主なターゲットとしています。

---
## 主な機能・特徴

- CEF + mpv構成 — Web UIの柔軟性とネイティブ動画再生性能を両立
- クロスプラットフォーム対応 — Linux、macOS、Windowsで動作
- マルチアーキテクチャビルド — x86_64、ARM64、Apple Silicon向けに提供
- 複数の配布形式 — AppImage、Flatpak、ネイティブパッケージに対応
- mpvコマンドライン直接アクセス — 上級ユーザー向けの再生オプション調整
- nightlyビルド配布 — GitHub Actions経由で継続的に最新版を提供
- justによる開発基盤 — パッケージング・テスト・lintの整備

---
## トレンド入り理由の推測

このプロジェクトはRustで書かれた1,074コミット規模の活発な開発が続くクライアントで、フォーマルなリリースはまだ無くnightlyビルド中心という「開発中だが実用段階に入りつつある」フェーズにあります。1日で54スターという伸びは、Jellyfinユーザーコミュニティ内での口コミ的な拡散や、Redditなどでの紹介が引き金になった可能性が高いです。

Jellyfin自体、Plexなど商用メディアサーバーからの移行先として近年注目を集め続けており、その周辺エコシステムのクライアントアプリが充実することはコミュニティにとって関心の高いトピックです。特にCEFとmpvという「Webの柔軟性とネイティブ動画再生性能の両立」を狙った技術選定は、既存のElectron製クライアントよりも軽量・高性能であることを期待させ、自ホスト(self-hosted)コミュニティで話題になりやすい要素と言えます。

---
## 関連リンク

- https://github.com/andrewrabert/jellium-desktop

---
## メモ
