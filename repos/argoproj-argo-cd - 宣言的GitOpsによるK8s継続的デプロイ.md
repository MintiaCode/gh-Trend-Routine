---
url: https://github.com/argoproj/argo-cd
saved: 2026-07-08
tags:
  - go
  - trending
  - argo
  - argo-cd
  - cd
  - ci-cd
  - cicd
  - continuous-delivery
  - continuous-deployment
  - devops
  - docker
  - gitops
  - hacktoberfest
  - helm
  - jsonnet
  - kubernetes
  - kustomize
  - pipeline
category: GitHub Trending
status: 未読
rating:
---

# argoproj/argo-cd

▎ 宣言的GitOpsによるK8s継続的デプロイ

ライセンス: Apache-2.0
言語: Go
スター数: ⭐ 23408 (+20 今日)
トレンド順位: #6 (2026-07-08)

---
## 概要

Argo CDは、Kubernetes向けの宣言的GitOps継続的デリバリーツールである。従来の手動デプロイやスクリプトベースの運用では、環境間の差分管理や変更履歴の追跡が煩雑になりがちだったが、Argo CDはアプリケーションの望ましい状態をGitリポジトリで一元管理し、実際のクラスタ状態と自動的に同期させることでこの課題を解決する。すべてのデプロイがバージョン管理され、監査可能かつ理解しやすい形で自動化される点が最大の特徴で、Helm・Kustomize・Jsonnetといった主要なマニフェスト管理ツールにも対応している。SLSA 3認証やCII Best Practices、OpenSSF Scorecardといった品質・セキュリティ指標を公開しており、エンタープライズ環境でも安心して採用できる。Kubernetes運用に携わるDevOpsエンジニアやSREチームが主なターゲットユーザーで、CI/CDパイプラインの信頼性と可視性を高めたい組織に広く使われている。

---
## 主な機能・特徴

- 宣言的GitOps — Gitリポジトリを唯一の信頼できる情報源として自動同期
- Helm/Kustomize/Jsonnet対応 — 主要なK8sマニフェスト管理ツールをサポート
- 自動化・監査可能なデプロイ — 変更履歴が追跡可能で透明性が高い
- SLSA 3 / CII Best Practices / OpenSSF Scorecard認定 — 高いセキュリティ基準
- ライブデモ環境 — 実際の挙動をブラウザ上で確認可能
- 活発なコミュニティ — GitHub Discussions・Slack・定例ミーティングで継続的にサポート
- マルチクラウド/機械学習基盤など幅広いユースケースの実例が豊富

---
## トレンド入り理由の推測

argo-cdは2018年から続くCNCF傘下の成熟したプロジェクトであり、23,000以上のスターを持つデファクトスタンダードのGitOpsツールである。本日のスター増加数は20件と小規模だが、pushed_atが本日(2026-07-08)であることから、直近のコミットやリリースがコミュニティの注目を再び集めていると考えられる。

KubernetesのGitOps運用は依然として企業のインフラ構築において重要な位置を占めており、セキュリティ認証(SLSA 3など)を積極的に取得している点も、サプライチェーンセキュリティへの関心が高まる昨今の潮流と合致する。老舗プロジェクトであっても継続的なメンテナンスとコミュニティ活動が評価され、定期的にトレンド入りするパターンの一つと推測される。

---
## 関連リンク

- https://github.com/argoproj/argo-cd
- https://argo-cd.readthedocs.io

---
## メモ
