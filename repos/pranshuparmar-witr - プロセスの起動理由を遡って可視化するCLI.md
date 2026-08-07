---
url: https://github.com/pranshuparmar/witr
saved: 2026-08-07
tags:
  - go
  - trending
  - cli
  - containers
  - devops
  - docker
  - freebsd
  - go
  - golang
  - incident-response
  - kubernetes
  - linux
  - macos
  - monitoring
  - observability
  - process-management
  - sysadmin
  - systemd
  - terminal
  - troubleshooting
  - tui
  - windows
category: GitHub Trending
status: 未読
rating:
---

# pranshuparmar/witr

▎ プロセスの起動理由を遡って可視化するCLI

ライセンス: Apache-2.0
言語: Go
スター数: ⭐ 19600 (+308 今日)
トレンド順位: #16 (2026-08-07)

---
## 概要

witr(Why Is This Running?)は、「なぜこのプロセスが動いているのか」というただ一つの問いに答えるために作られたCLIツールです。`ps`や`top`、`lsof`、`ss`、`systemctl`、`docker ps`といった既存ツールは「何が動いているか」という状態は示せても、複数のレイヤーにまたがるsupervisor・コンテナ・サービス・シェルなどの因果関係を人間が手作業で突き合わせる必要がありました。witrはプロセス、ポート、コンテナ、ファイルを起点として、それを起動した正確な連鎖を1コマンドで遡り、人間が読みやすい出力・機械可読なJSON・インタラクティブなTUIダッシュボードのいずれかで提示します。Linux、macOS、Windows、FreeBSDに対応した単一の静的バイナリとして配布され、Homebrew・Conda・AUR・Winget・npmなど多数のパッケージマネージャーからもインストール可能です。SRE、システム管理者、インシデント対応担当者など、本番環境のトラブルシューティングを日常的に行うエンジニアを主な対象としています。

---
## 主な機能・特徴

- 起動連鎖のトレース — プロセス/ポート/コンテナ/ファイルから起点となった一連の因果関係を可視化
- インタラクティブTUI — ダッシュボード形式で視覚的に調査可能
- 機械可読JSON出力 — スクリプトや自動化パイプラインへの組み込みが容易
- ブラウザ体験版 — インストール不要のシミュレーション環境でお試し可能
- マルチプラットフォーム対応 — Linux/macOS/Windows/FreeBSDで単一バイナリとして動作
- 豊富な配布チャネル — Homebrew、Conda、AUR、Winget、npmなど多数のパッケージマネージャーに対応
- インシデント対応向け設計 — systemd・Docker・Kubernetesなど複数レイヤーを横断した原因究明を支援

---
## トレンド入り理由の推測

witrは本日308スターを獲得しており、Hacker NewsやProduct Hunt、Trendshiftへの掲載実績がREADMEに明記されていることから、複数のコミュニティ発信を経て話題が拡散した典型的なバイラル型トレンドと考えられます。「なぜこのプロセスが動いているのか」という、誰もが経験したことのある地味だが普遍的な悩みにピンポイントで答えるツールであることが、幅広い層のエンジニアの共感を呼びやすい要因です。

技術的には、`ps`や`lsof`など既存の定番コマンドが担ってきた領域に対し、systemd・コンテナ・supervisorをまたいだ因果関係の可視化という明確な差別化ポイントを持ち込んでいる点、そしてブラウザで試せるインタラクティブなデモを用意している点が、実際に試してみたくなる導線として機能し、SNSでの拡散とスター増加を後押ししたと推測されます。Go言語製の単一バイナリで多数のOS・パッケージマネージャーに対応している手軽さも、実務者による即採用につながっていると考えられます。

---
## 関連リンク

- https://github.com/pranshuparmar/witr
- https://pranshuparmar.github.io/witr/

---
## メモ

