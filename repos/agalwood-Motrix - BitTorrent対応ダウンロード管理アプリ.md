---
url: https://github.com/agalwood/Motrix
saved: 2026-08-17
tags:
  - typescript
  - trending
  - aria2
  - bittorrent
  - bt
  - download
  - download-manager
  - electron
  - linux
  - mac
  - macos
  - magnet
  - motrix
  - torrent
  - windows
category: GitHub Trending
status: 未読
rating:
---

# agalwood/Motrix

▎ BitTorrent対応ダウンロード管理アプリ

ライセンス: MIT
言語: TypeScript
スター数: ⭐ 53000 (+295 今日)
トレンド順位: #11 (2026-08-17)

---
## 概要

Motrixは、HTTP/FTPダウンロードからBitTorrent、マグネットリンクまで幅広いプロトコルに対応するクロスプラットフォームのダウンロードマネージャーである。2018年からDr_rOot氏を中心に開発が続けられており、現在はv2(コードネームTurbo)としてElectron・React・TypeScriptによる全面的な作り直しが進行中(ベータ版)。従来のダウンロードマネージャーは広告過多だったりUIが煩雑だったりする製品が多い中、Motrixはシンプルで分かりやすいインターフェースとダークモードを備え、macOS・Windows・Linuxのデスクトップアプリに加え、ヘッドレスサーバー向けのDocker配布やnpm経由のCLIクライアントも提供する。ダウンロードエンジンにはMotrix独自メンテのaria2forkを採用し、UPnP/NAT-PMPによる自動ポートマッピングやトラッカーの自動更新、プラグインのQuickJSサンドボックス実行などエンスージアスト向けの機能も充実。自宅サーバーやNASでの常時稼働ダウンローダーを求めるユーザー、広告なしで軽量なダウンロードマネージャーを探す一般ユーザーの双方が対象となる。

---
## 主な機能・特徴

- マルチプロトコル対応 — HTTP、FTP、BitTorrent、マグネットリンクなど幅広い形式のダウンロードをサポート
- BitTorrent詳細制御 — ファイル単位の選択ダウンロードや、健全性チェック付きトラッカー管理を搭載
- ネットワーク自動最適化 — UPnP/NAT-PMPによるポートマッピングで面倒な手動設定を省略
- 同時実行制御 — 最大10ダウンロード・タスクあたり64スレッドまでの並列処理に対応
- プラグインサンドボックス — QuickJSによる安全なプラグイン実行環境を提供
- マルチプラットフォーム配布 — macOS/Windows/LinuxのGUIに加え、Docker・CLIでのヘッドレス運用も可能
- 多言語UI — 30以上の言語に対応したインターフェースを提供
- ブラウザ拡張連携 — Chrome/Firefox向け拡張機能でワンクリックダウンロードに対応

---
## トレンド入り理由の推測

累計スターが5万を超える成熟したプロジェクトでありながら、今日1日で+295という着実な伸びを見せているのは、単発のバズよりも継続的な認知拡大の結果と考えられる。背景にあるのはv2(Turbo)への全面リニューアルで、Electron・React 19・TypeScriptという最新スタックへの刷新やaria2forkの継続メンテナンスなど、long-standingなOSSが「枯れた技術」で終わらず現役でアップデートされ続けている点が、GitHub上での再発見や再評価につながっている可能性が高い。

多くの商用ダウンロードマネージャーが広告表示やサブスクリプション化を進める中、Motrixは無料・オープンソースかつ広告なしでBitTorrentからHTTPまで一括管理できる希少な選択肢であり続けている。自宅サーバーやNASでの常時稼働ニーズ、あるいは大容量ファイルのBitTorrent配布が再び注目される局面(大規模データセットやAIモデル配布など)において、UPnP自動設定やヘッドレスDocker運用といった実用機能が改めて評価され、RedditやHacker Newsなどのコミュニティで言及されたことがスター増加とトレンド入りの一因になったと推測される。

---
## 関連リンク

- https://github.com/agalwood/Motrix
- https://motrix.app

---
## メモ
