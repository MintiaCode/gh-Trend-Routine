---
url: https://github.com/openai/codex-plugin-cc
saved: 2026-07-02
tags:
  - javascript
  - trending
category: GitHub Trending
status: 未読
rating:
---

# openai/codex-plugin-cc

▎ Claude CodeでCodexを使うプラグイン

ライセンス: Apache-2.0
言語: JavaScript
スター数: ⭐ 22500 (+448 今日)
トレンド順位: #13 (2026-07-02)

---
## 概要

codex-plugin-cc は、OpenAIが公式に提供するClaude Code向けプラグインで、Claude Codeのセッションを離れることなくOpenAIのCodexの機能（コードレビューやタスク委譲）を呼び出せるようにするツールである。`/codex:review` による通常のコードレビュー、`/codex:adversarial-review` による設計・実装方針そのものを問い直す辛口レビュー、`/codex:rescue` によるバグ調査やタスクの委譲・引き継ぎなど、複数のワークフローをコマンドとして提供する。利用にはChatGPTサブスクリプションまたはOpenAI APIキーが必要で、ローカルのCodex CLIおよびappサーバーを経由して動作し、既存の`~/.codex/config.toml`の設定（モデル選択や推論強度など）をそのまま引き継ぐ。Claude CodeとCodexの両方を併用している開発者や、複数のAIコーディングツールを横断してレビュー精度を高めたいチームを主な対象としている。

---
## 主な機能・特徴

- コードレビュー — `/codex:review`で未コミット差分やブランチ比較をレビュー
- 辛口レビュー — `/codex:adversarial-review`で設計方針自体を問い直す
- タスク委譲 — `/codex:rescue`でバグ調査・作業引き継ぎをCodexに依頼
- セッション連携 — `/codex:transfer`で永続的なCodexスレッドを作成
- ジョブ管理 — `/codex:status`・`/codex:result`・`/codex:cancel`でバックグラウンドタスクを管理
- 設定共有 — 既存のCodex CLI設定（モデル・推論強度）を自動継承
- 簡単導入 — マーケットプレイス経由でのワンステップインストール

---
## トレンド入り理由の推測

OpenAIが自社のCodexをライバルであるはずのClaude Code上で公式に使えるようにするプラグインを公開したこと自体が、AI開発者コミュニティにとって大きな話題性を持つ。競合するAIコーディングツール同士が公式に統合されるという異例の動きは、SNSやニュースサイトで急速に拡散されやすい性質を持つ。

リリースv1.0.5（2026年6月23日）と直近のアップデートであることに加え、今日だけで448スターという急増を記録しており、公開直後の話題性の高さを裏付けている。単一ツールに固執せず複数のAIエージェントを併用する「マルチエージェント開発」というトレンドとも合致しており、レビューの多角化・精度向上を求める開発者の関心を集めたことがトレンド入りの主因と推測される。

---
## 関連リンク

- https://github.com/openai/codex-plugin-cc

---
## メモ
