---
url: https://github.com/microsoft/mxc
saved: 2026-06-06
tags:
  - rust
  - trending
  - sandbox
  - security
  - containment
  - ai-agent
  - microsoft
category: GitHub Trending
status: 未読
rating:
---

# microsoft/mxc

▎ AIツール実行向けポリシー駆動サンドボックス

ライセンス: MIT
言語: Rust
スター数: ⭐ 541 (+57 今日)
トレンド順位: #16 (2026-06-06)

---
## 概要

Microsoft eXecution Container（MXC）はMicrosoftが開発した、AIモデルの出力・プラグイン・ツールなど信頼できないコードを安全に実行するためのサンドボックスシステム。Rustで実装されたコアエンジンがWindows・Linux・macOSのクロスプラットフォームで動作し、各OSの標準的なサンドボックス技術（Windows Sandbox・Bubblewrap・Seatbelt）をバックエンドとして活用する。JSONベースのポリシー定義によりファイルシステム・ネットワーク・UIアクセスを細粒度で制御し、最小権限原則に基づく多層的な分離を実現する。TypeScript SDKもnpmパッケージとして提供されており、Node.jsアプリケーションへの統合も容易。AIエージェント・コーディングアシスタントが信頼できないコードを実行するユースケースを主なターゲットとしており、MicrosoftのAIシステム安全性への取り組みを示すオープンソースプロジェクトとして公開されている。

---
## 主な機能・特徴

- クロスプラットフォームサンドボックス — Windows 11/Linux/macOS で各OS標準技術による隔離を実現
- JSONポリシーエンジン — FS・ネットワーク・UIアクセスを細粒度で制御するセキュリティポリシー定義
- 複数バックエンド対応 — Windows Sandbox・LXC・Bubblewrap・Seatbelt から環境に合わせて選択
- TypeScript SDK — npmパッケージ経由でNode.jsアプリケーションへ即座に統合可能
- 多層分離アーキテクチャ — ProcessContainerからOS全体分離まで段階的な隔離レベルを提供
- AIツール実行向け設計 — モデル出力・未検証プラグイン・ツール実行のセキュリティリスクを排除
- MIT ライセンス — Microsoftのオープンソースとして自由に利用・拡張・貢献が可能

---
## トレンド入り理由の推測

541スターという比較的少ない総数ながら1日57スターという急激な増加を記録しており、リリース直後または大きな公式アナウンスがあったことを強く示唆する。MicrosoftがAIエージェント向けセキュリティインフラとして新たに公開した、あるいは大規模な更新が行われたばかりのプロジェクトである可能性が高い。

AIエージェントが任意のコードを自動実行するユースケース（Claude Code・GitHub Copilot・AI自律エージェント全般）が急速に普及する2026年において、「信頼できないコードを安全に実行する」という問題はセキュリティエンジニアとAI開発者双方の最重要課題のひとつ。MXCはこの課題に対してMicrosoftがオープンソースで提供するソリューションであり、タイムリーさと信頼性の高さから一気に注目を集めた。

Rust実装・クロスプラットフォーム対応・TypeScript SDKというスタックはGitHub Trendで人気を集めやすい要素が揃っており、Rustコミュニティ・AI安全性研究者・フロントエンドエンジニアと複数のコミュニティから同時に関心を引いたと推測される。

---
## 関連リンク

- https://github.com/microsoft/mxc

---
## メモ

