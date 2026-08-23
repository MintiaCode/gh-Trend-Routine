---
url: https://github.com/dani-garcia/vaultwarden
saved: 2026-08-23
tags:
  - rust
  - trending
  - bitwarden
  - bitwarden-rs
  - docker
  - rocket
  - rust
  - vaultwarden
category: GitHub Trending
status: 未読
rating:
---

# dani-garcia/vaultwarden

▎ Rust製Bitwardenサーバー実装

ライセンス: AGPL-3.0
言語: Rust
スター数: ⭐ 65900 (+95 今日)
トレンド順位: #14 (2026-08-23)

---
## 概要

Vaultwardenは、パスワード管理サービスBitwardenのクライアントAPIを、Rustで独自実装した非公式の互換サーバーです。公式のBitwardenクライアント(モバイル・デスクトップ・ブラウザ拡張)をそのまま利用しながら、サーバー側だけを軽量なVaultwardenに置き換えられる点が最大の特徴で、リソース消費の大きい公式サーバーを動かすのが難しい自宅サーバーやVPS、Raspberry Piなどでのセルフホスティングに最適化されています。個人用ボルト、Send機能、添付ファイル、ウェブサイトアイコン取得、個人用APIキーに加え、組織機能(コレクション、パスワード共有、メンバー権限、グループ、イベントログ、管理者パスワードリセット、ディレクトリ連携、ポリシー)、多要素認証(Authenticator、メール、FIDO2 WebAuthn、YubiKey、Duo)、緊急アクセスなど、Bitwardenの主要機能をほぼ網羅しています。Docker/Podmanコンテナイメージとして配布されており、Rocket Webフレームワーク上に構築され、リバースプロキシ経由でのHTTPS化が推奨されています。自宅や小規模組織で低コストかつプライバシーを重視したパスワード管理基盤を構築したいユーザーが主な対象です。

---
## 主な機能・特徴

- Bitwarden Client APIのほぼ完全な互換実装(個人ボルト・Send・添付ファイルなど)
- 組織機能フル対応 — コレクション、パスワード共有、グループ、イベントログ、ポリシー
- 多要素認証を幅広くサポート — Authenticator、FIDO2 WebAuthn、YubiKey、Duoなど
- 管理者用Webバックエンド(admin page)を搭載
- Docker/Podman/ghcr.io/Quay.io向けの軽量コンテナイメージを配布
- カスタマイズされたWeb Vaultクライアントをコンテナに同梱
- Rust製で低リソース環境(自宅サーバー、Raspberry Pi等)でも高速動作

---
## トレンド入り理由の推測

Vaultwardenは既に6万5千件超のスターを持つ成熟したプロジェクトであり、本日95件という穏やかなペースでの伸びは急上昇というより、パスワード管理・セルフホスティングへの関心が継続的に高い分野での安定した支持を反映していると考えられます。

近年、クラウドサービスへの依存やデータ主権への懸念が高まる中、「自分のデータは自分のサーバーで管理する」というセルフホスト志向がDevOpsコミュニティを中心に広がっており、公式Bitwardenよりも軽量なRust実装であるVaultwardenは、その代表的な選択肢としてたびたび話題に上ります。特にDockerやHomelab関連のコミュニティ、あるいはパスワード管理サービスの値上げや規約変更のニュースが出るたびに関心が再燃しやすい性質のプロジェクトです。

Rustによる高いパフォーマンスと省リソース性、そして公式Bitwardenクライアントとの完全な互換性を維持しながら独自にメンテナンスを続けている実績が、長期にわたり安定してスターを積み重ねている理由と言えます。

---
## 関連リンク

- https://github.com/dani-garcia/vaultwarden

---
## メモ

