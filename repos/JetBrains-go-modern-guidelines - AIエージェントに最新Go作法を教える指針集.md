---
url: https://github.com/JetBrains/go-modern-guidelines
saved: 2026-08-27
tags:
  - go
  - trending
  - ai-agents
  - coding-agent
  - developer-tools
  - go
  - golang
  - guidelines
category: GitHub Trending
status: 未読
rating:
---

# JetBrains/go-modern-guidelines

▎ AIエージェントに最新Go作法を教える指針集

ライセンス: Apache-2.0
言語: Go
スター数: ⭐ 2018 (+314 今日)
トレンド順位: #5 (2026-08-27)

---
## 概要

go-modern-guidelinesは、AIコーディングエージェントに最新のGoの書き方(イディオム)を教えるためのガイドライン集です。LLMは学習データの鮮度の遅れ(トレーニングデータラグ)と、古いパターンほど学習データに多く出現する頻度バイアスという2つの課題を抱えており、その結果、Go 1.0〜1.27の広い範囲にわたる新機能を無視して、古い書き方のコードを生成しがちです。本プロジェクトは`max(a, b)`や`slices.Contains`といった組み込み関数、Go 1.26で追加された`new(42)`によるポインタ生成や`errors.AsType[T](err)`による型安全なエラーハンドリングなど、最新のGoイディオムをエージェントに提示します。`go.mod`からプロジェクトのGoバージョンを自動検出する仕組みも備え、Junie CLI、Claude Code、Codex、Cursorなど複数のAIコーディングエージェント向けにマーケットプレイス経由でインストールできます。対象ユーザーは、AIエージェントを使ってGoコードを書く開発者や、エージェントの出力品質を向上させたいチームです。

---
## 主な機能・特徴

- Go 1.0から1.27までの幅広いバージョンのモダンなイディオムを網羅
- `max(a, b)`や`slices.Contains`などの組み込み関数・標準ライブラリの活用を提案
- Go 1.26の新機能(`new(42)`、`errors.AsType[T]`)にも対応
- `go.mod`からプロジェクトのGoバージョンを自動検出
- Junie CLI、Claude Code、Codex、Cursorなど複数エージェントに対応したインストール方法
- プロジェクトを直接変更せず、ガイドラインの提示に徹する設計
- `npx skills add`で他のエージェントにも導入可能

---
## トレンド入り理由の推測

このリポジトリが今日トレンド入りした最大の要因は、「AIコーディングエージェント向けスキル・ガイドライン」という、現在GitHub Trendingで非常に人気の高いカテゴリに属している点です。トレンドページには他にも`anthropics/claude-plugins-official`や`K-Dense-AI/scientific-agent-skills`、`ConardLi/garden-skills`など、AIエージェントの能力を拡張するスキル・プラグイン系リポジトリが多数ランクインしており、業界全体でAIエージェントの「専門知識の後付け」が大きな潮流になっていることがうかがえます。

JetBrainsという実績あるIDEベンダーが公式に公開しているという信頼性も、開発者からの注目を集めやすい要因です。特にAIがコードを書く際に「知らないうちに古い書き方をしてしまう」という実務上よくある問題に対し、具体的かつ実用的な解決策を提示している点が、Go開発者コミュニティで急速に支持を広げていると考えられます。

また、Claude Code・Cursor・Codexなど複数の主要なAIコーディングツールに対応したマルチプラットフォーム設計も、幅広い開発者層への訴求力を高め、拡散を後押ししていると推測されます。

---
## 関連リンク

- https://github.com/JetBrains/go-modern-guidelines

---
## メモ
