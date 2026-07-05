---
url: https://github.com/gastownhall/gastown
saved: 2026-07-05
tags:
  - go
  - trending
category: GitHub Trending
status: 未読
rating:
---

# gastownhall/gastown

▎ マルチエージェント統括ワークスペース

ライセンス: MIT License
言語: Go
スター数: ⭐ 16300 (+48 今日)
トレンド順位: #18 (2026-07-05)

---
## 概要

Gas Townは、Claude Code・GitHub Copilot・Codex・Geminiなど複数のAIコーディングエージェントを同時に運用するためのワークスペースマネージャーです。エージェントが再起動するたびにコンテキストを失う問題や、4〜10体を超えるエージェントを人手で調整する煩雑さを解決するために、作業状態をgit連携の「Hooks」に永続化し、20〜30体規模のエージェントでも破綻なく運用できる仕組みを提供します。中心となる「Mayor」がAIコーディネーターとして全体を統括し、プロジェクト単位の「Rig」、ユーザー自身が作業する「Crew」、使い捨てで動く作業エージェント「Polecat」といった階層構造で役割を分担します。作業単位はBeadsと呼ばれるgitバックエンドの課題管理システムで追跡され、Witness・Deacon・Dogsによる3層の監視体制が異常検知と自動復旧を担うなど、大規模なマルチエージェント運用を前提に設計された本格的な基盤です。

---
## 主な機能・特徴

- Git連携の永続化 — HooksによりエージェントごとにGit worktreeで作業状態を保存
- Mayor/Rig/Crew/Polecats階層 — 役割別に整理されたエージェント編成モデル
- Beadsによる課題管理 — 作業単位をgitバックエンドで一元追跡
- 3層監視システム — Witness・Deacon・Dogsが異常検知と自動復旧を実施
- Refineryマージキュー — Borsスタイルの検証つき自動マージ処理
- Escalation機能 — 重大度別に問題をMayor/Overseerへ自動エスカレーション
- Wasteland — 複数のGas Town間で作業を融通し合う連合ネットワーク

---
## トレンド入り理由の推測

複数のAIコーディングエージェントを並行運用する「マルチエージェントオーケストレーション」は2026年の開発ツール領域における主要トレンドの一つで、本日のトレンドにも同系統のherdrやMiroFishが並んでいます。Gas Townは単なる並列実行にとどまらず、Beads・Molecules・Wastelandといった独自概念を通じて作業の永続化とエージェント間連携を体系化しており、その設計の作り込みが開発者コミュニティで話題になっていると考えられます。

Go言語製でHomebrewやnpm経由で手軽に導入できる点や、Claude Code・Copilot・Codex・Geminiなど主要なエージェントランタイムを横断的にサポートする点も、特定ベンダーに縛られたくない開発者層への訴求力となり、着実なスター増加につながっているとみられます。

---
## 関連リンク

- https://github.com/gastownhall/gastown

---
## メモ
