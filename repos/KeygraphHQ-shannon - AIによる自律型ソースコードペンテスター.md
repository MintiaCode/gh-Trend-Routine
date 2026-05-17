---
url: https://github.com/KeygraphHQ/shannon
saved: 2026-05-17
tags:
  - typescript
  - trending
  - security-audit
  - penetration-testing
  - pentesting
  - security-automation
  - security-tools
category: GitHub Trending
status: 未読
rating:
---

# KeygraphHQ/shannon

▎ AIによる自律型ソースコードペンテスター

ライセンス: AGPL-3.0
言語: TypeScript
スター数: ⭐ 42,600 (+213 今日)
トレンド順位: #12 (2026-05-17)

---
## 概要

ShannonはKeygraph社が開発した自律型ホワイトボックスAIペネトレーションテスターです。ウェブアプリケーションとAPIのソースコードを解析し、攻撃ベクターを特定して実際のエクスプロイトを実行することで脆弱性を証明します。インジェクション攻撃・認証バイパス・SSRF・XSSなど主要な脆弱性クラスをカバーし、「エクスプロイトによる証明」という方針のもと、実際にPoCが成功した脆弱性のみをレポートします。Shannon Lite（AGPL-3.0、ローカルテスト向け）とShannon Pro（商用、SAST・SCA・シークレットスキャン統合）の2エディションがあります。Claude・AWS Bedrock・Google Vertex AI上のAnthropicモデルをバックエンドとして使用し、Dockerが必要です。サンドボックス環境専用であり、明示的な書面による許可なしに本番システムへの使用は禁止されています。

---
## 主な機能・特徴

- ソースコード解析 — ホワイトボックス方式でコードから攻撃ベクターを自動特定
- エクスプロイト実証 — ブラウザ自動化とCLIツールで実際の攻撃を実行し証明
- 主要脆弱性クラス対応 — インジェクション・認証バイパス・SSRF・XSSをカバー
- Claude/Bedrock/Vertex統合 — Anthropicモデルを複数バックエンドで選択可能
- npxワンコマンド起動 — `npx @keygraph/shannon start`で即座にペンテスト開始
- デュアルエディション — オープンソースのLiteと商用のProで用途別に対応
- AGPL-3.0ライセンス — Lite版は研究・教育・ローカルテストに無料で利用可能

---
## トレンド入り理由の推測

Shannonが42,600という大規模スターを持ちながら本日213スターを獲得したのは、AIを使ったセキュリティテストへの継続的な高い関心を反映しています。AppSec（アプリケーションセキュリティ）の自動化はDevSecOpsの重要テーマとなっており、「CIパイプラインに組み込める自律型ペンテスト」というコンセプトが企業セキュリティチームから強い支持を得ています。

v1.2.0（2026年5月6日）のリリースから約2週間でのトレンド継続は、セキュリティカンファレンス（BlackHat・DEF CON準備期やBSidesシーズン）での話題や、セキュリティ研究者コミュニティでの口コミ拡散を示唆しています。AnthropicのClaude APIをバックエンドとして採用していることで、AI能力向上とともにセキュリティテスト能力も自動的に向上するという独自の強みがあります。

「エクスプロイトによる証明のみレポート」というゼロノイズ方針は、従来のSASTツールが抱える大量の誤陽性問題を解決するアプローチとして業界から注目されており、実践的なセキュリティエンジニアに刺さる設計思想です。

---
## 関連リンク

- https://github.com/KeygraphHQ/shannon
- https://keygraph.io/

---
## メモ
