---
url: https://github.com/actions/checkout
saved: 2026-07-02
tags:
  - typescript
  - trending
category: GitHub Trending
status: 未読
rating:
---

# actions/checkout

▎ GitHub Actions公式リポジトリ取得アクション

ライセンス: MIT
言語: TypeScript
スター数: ⭐ 8100 (+5 今日)
トレンド順位: #9 (2026-07-02)

---
## 概要

actions/checkout は、GitHub Actions のワークフロー内でリポジトリのコードを `$GITHUB_WORKSPACE` 配下にチェックアウトするための公式アクションである。CI/CDパイプラインを組む上でほぼ全てのワークフローの最初のステップとして利用される基盤的なツールであり、GitHub自身がメンテナンスしている。特定のref（ブランチ・タグ・SHA）の指定、フェッチ深度の制御、サブモジュールやGit LFSのサポート、sparse-checkoutによる部分取得など、CI環境でリポジトリを扱う上で必要な機能を幅広くカバーする。近年はセキュリティ強化にも力を入れており、フォークからのpull_requestを起点とする「pwn request」攻撃を防ぐため、`pull_request_target` や `workflow_run` イベント経由でのフォークPRコードの自動チェックアウトをデフォルトで拒否する設計になっている。対象ユーザーはGitHub Actionsを使う全ての開発者・組織である。

---
## 主な機能・特徴

- 標準チェックアウト — 対象リポジトリを$GITHUB_WORKSPACEに取得
- 柔軟なref指定 — ブランチ・タグ・コミットSHAを指定可能
- 認証情報管理 — PATやSSHキーによる認証、post-jobでの自動クリーンアップ
- セキュリティ強化 — v7でフォークPRの危険なチェックアウトをデフォルト拒否
- sparse-checkout対応 — 必要なファイルのみを選択的に取得
- Git LFS・サブモジュール対応 — 大容量ファイルや依存リポジトリの取得
- REST APIフォールバック — Git 2.18未満の環境でも動作可能

---
## トレンド入り理由の推測

actions/checkout はGitHub Actionsのデファクトスタンダードとして常時大量に利用されているリポジトリであり、今日の新規スター+5という数値自体は小さいが、v7.0.0という新しいメジャーリリース（2026年6月18日）が出た直後のタイミングで、フォークPRのセキュリティ制御という重要な変更が含まれていることが再注目の要因と推測される。

サプライチェーン攻撃やCI/CDパイプラインを狙った「pwn request」型の脆弱性が近年のセキュリティ業界で継続的に話題になっており、それに対する公式な防御策のアップデートという性質上、DevOps・セキュリティ双方のコミュニティで参照・共有されやすい。多くのリポジトリで直接依存する基盤アクションであるため、バージョンアップ時の挙動変化情報として広く閲覧されていると考えられる。

---
## 関連リンク

- https://github.com/actions/checkout

---
## メモ
