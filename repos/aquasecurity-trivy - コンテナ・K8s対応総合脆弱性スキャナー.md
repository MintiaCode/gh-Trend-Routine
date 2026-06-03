---
url: https://github.com/aquasecurity/trivy
saved: 2026-06-03
tags:
  - go
  - trending
  - go
  - docker
  - kubernetes
  - golang
  - security
  - containers
  - iac
  - vulnerability
  - infrastructure-as-code
  - vulnerability-detection
  - hacktoberfest
  - vulnerability-scanners
  - security-tools
  - devsecops
  - misconfiguration
category: GitHub Trending
status: 未読
rating:
---

# aquasecurity/trivy

▎ コンテナ・K8s対応総合脆弱性スキャナー

ライセンス: Apache-2.0
言語: Go
スター数: ⭐ 35300 (+26 今日)
トレンド順位: #3 (2026-06-03)

---
## 概要

Trivyは、コンテナイメージ・Kubernetes・コードリポジトリ・仮想マシン・クラウド環境など多様なターゲットを対象とした包括的なセキュリティスキャナーです。AquaSecurityが開発するオープンソースプロジェクトで、CVE（共通脆弱性識別子）に基づく脆弱性検出、IaC（Infrastructure as Code）の設定ミス、機密情報の漏洩、ソフトウェアライセンスの問題まで一括で診断できます。OSパッケージから主要プログラミング言語の依存ライブラリまで幅広くカバーし、GitHub Actions・Kubernetesオペレーター・VS Codeプラグインなどとのインテグレーションも充実しています。DevSecOpsワークフローへの組み込みが容易で、CI/CDパイプラインでの自動セキュリティ診断ツールとして広く採用されています。

---
## 主な機能・特徴

- 脆弱性スキャン — CVEデータベースを使ってOSパッケージ・言語依存ライブラリの既知脆弱性を検出
- IaC診断 — Terraform・Kubernetes・Helm等のインフラコードの設定ミスを検出
- シークレット検出 — コードやコンテナ内の機密情報（APIキー・パスワード等）の漏洩を発見
- SBOMサポート — ソフトウェア部品表（SBOM）の生成・検査に対応
- マルチターゲット — コンテナ・ファイルシステム・Gitリポジトリ・VM・Kubernetesを横断してスキャン
- CI/CD統合 — GitHub Actions・GitLab CI等のパイプラインに簡単に組み込み可能
- 軽量・高速 — 単一バイナリで動作し、Dockerコマンド一発でも利用可能

---
## トレンド入り理由の推測

aquasecurity/trivyは35,000超のスターを持つ成熟したセキュリティツールで、1日あたり26スターというのは通常レベルです。GitHubのトレンドアルゴリズムは単純な日次スター数だけでなく、継続的なコミュニティ活動や一定期間のスター獲得ペースも考慮するため、安定した人気を誇るプロジェクトが定期的に登場します。

2026年現在、コンテナセキュリティとサプライチェーン攻撃対策が企業のセキュリティ戦略における最重要課題の一つとなっており、SBOMの法的要件化（特に米国政府機関向けソフトウェア）が注目を集めていることが背景にあります。Trivyはこれらのニーズに応える代表的ツールとして再認識されているとみられます。

最近v0.71.0リリースが行われたことも、既存ユーザーへのアップデート告知やセキュリティコミュニティでの共有を通じて新たなスターを集めた可能性があります。DevSecOpsの普及とともに、開発者自身がセキュリティスキャンを担う文化が定着しており、Trivyのようなシンプルに使える統合ツールへの需要が高まっています。

---
## 関連リンク

- https://github.com/aquasecurity/trivy
- https://trivy.dev

---
## メモ
