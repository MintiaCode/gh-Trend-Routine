---
url: https://github.com/different-ai/openwork
saved: 2026-07-29
tags:
  - typescript
  - trending
  - ai-workflows
  - mcp
  - desktop-app
  - open-source
category: GitHub Trending
status: 未読
rating:
---

# different-ai/openwork

▎ AIワークフロー共有デスクトップアプリ

ライセンス: 不明
言語: TypeScript
スター数: ⭐ 17800 (+58 今日)
トレンド順位: #9 (2026-07-29)

---
## 概要

OpenWorkは「AIワークフローを共有するための無料オープンソースデスクトップアプリ」であり、Claude CoworkやCodexといった商用のAIエージェント製品に対するオープンな代替を掲げるプロジェクトである。macOS・Windows・Linuxで動作し、一度作成したAIスキルやMCP連携を、複数のツール・チームメイト・マシン間で使い回せるようにすることを目的としている。中核にはModel Context Protocol（MCP）インターフェースがあり、`search_capabilities`（能力の検索）と`execute_capability`（実行）という2つのツールを公開することで、Claude Code、Cursor、Codex、ChatGPTなどMCP対応のエージェントと連携できる。デスクトップアプリはElectronとViteで構築され、pnpmワークスペースによるモノレポ構成で開発されている。個人開発者だけでなく、チーム単位でのアクセス制御やモデルプロバイダー制限、スキル/プラグインのマーケットプレイスを提供する「OpenWork Den」というガバナンス機能を通じて、企業導入も視野に入れている点が特徴である。

---
## 主な機能・特徴

- MCPサーバー — search_capabilities/execute_capabilityによるスキル検索・実行
- マルチエージェント対応 — Claude Code、Cursor、Codex、ChatGPT等と連携可能
- クロスプラットフォーム — macOS/Windows/Linux向けネイティブデスクトップアプリ
- OpenWork Den — チーム管理・アクセス制御・ポリシー適用のための管理基盤
- スキル/プラグインマーケットプレイス — 役割ベースでの割当と公開が可能
- Anthropic互換プラグインのインポート対応
- デスクトップ不要の運用 — MCP経由でエージェントに直接組み込み可能
- 活発な開発 — devブランチに4,000件超のコミット、多数のOSS Issue/PR

---
## トレンド入り理由の推測

OpenWorkは「Claude Coworkのオープンソース版代替」という明確な立ち位置を打ち出しており、これはMCP（Model Context Protocol）を軸としたエージェント連携がAI業界で急速に注目を集めている流れと合致する。総スター数1.78万に対し今日+58というペースは突発的な爆発というより、MCPエコシステムやAIエージェントのワークフロー共有に対する継続的な関心の高まりを反映していると考えられる。

特に、商用のクローズドなエージェント製品に対して「オープンでセルフホスト可能な代替」を提供するプロジェクトは、企業のデータガバナンスやベンダーロックイン回避のニーズと結びつきやすく、Cursor/Codex/Claude Codeなど複数のエージェントを横断して同じスキルを使い回せるという訴求が、複数ツールを併用する開発者層に強く響いていると推測される。OpenWork Denのようなチーム向けガバナンス機能の存在も、単なる個人向けツールを超えたエンタープライズ需要を取り込もうとする戦略の表れであり、これが継続的なトレンド入りの一因になっていると考えられる。

---
## 関連リンク

- https://github.com/different-ai/openwork
- https://openworklabs.com

---
## メモ
