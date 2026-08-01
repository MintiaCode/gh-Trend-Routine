---
url: https://github.com/github/gh-stack
saved: 2026-08-01
tags:
  - go
  - trending
  - cli
  - gh-extension
  - github
  - stacked-prs
category: GitHub Trending
status: 未読
rating:
---

# github/gh-stack

▎ スタックPRを管理するGitHub CLI拡張

ライセンス: MIT
言語: Go
スター数: ⭐ 776 (+90 今日)
トレンド順位: #7 (2026-08-01)

---
## 概要

gh-stackはGitHub公式が開発するGitHub CLI（gh）拡張で、スタックドPR（Stacked Pull Requests）と呼ばれる開発手法を支援するツールである。大きな変更を、互いに積み重なる小さくレビューしやすいPRの連鎖に分割する際に発生する、ブランチ作成・リベース維持・PRベースブランチの設定・階層間の移動といった煩雑な作業を自動化する。スタックはtrunkブランチ（通常main）を起点に、各ブランチが直下のブランチに依存する順序付きリストとして管理され、`gh stack init`でスタックを開始し、`gh stack add`で新しい層を追加、`gh stack submit`でPRをまとめて作成・リンクできる。スタックのメタデータは`.git/gh-stack`にローカル保存され、git rerereを自動有効化することで、リベース時のコンフリクト解決を記憶する。AIコーディングエージェント向けにgh-stackスキルも提供されており、Claude Code等のエージェントがスタック運用を理解した上で作業できる。大規模な変更を小さな単位でレビューしたいチーム開発者が主な対象ユーザーである。

---
## 主な機能・特徴

- gh stack init/add/push/submit — スタック作成からPR一括提出までをコマンド化
- 自動リベース管理 — 各層のブランチを最新状態に保つ
- git rerere自動有効化 — リベース時のコンフリクト解決を記憶し再利用
- インタラクティブpicker — checkout時にローカル/リモートのスタックを検索・選択可能
- PRベース自動設定 — 各PRのベースを直下のブランチに自動リンク
- AIエージェント向けスキル — `gh skill install`でClaude Code等に統合可能
- GitHub公式提供 — GitHub社自身が開発・メンテナンスするgh拡張

---
## トレンド入り理由の推測

本ツールはGitHub公式（github organization）が提供する新しいgh CLI拡張であり、スタックドPRというワークフローは近年Graphite等のツールで人気が高まっている開発手法である。GitHub自身がこの手法をネイティブサポートする拡張を出したことは、大規模リポジトリでのレビュー効率化を求める開発者コミュニティにとって大きなニュースであり、公開直後から一気に注目を集めたと考えられる。

さらに、「AIエージェント統合」として`gh skill install github/gh-stack`でClaude Codeなどのコーディングエージェントにこのワークフローを教えられる機能を備えている点も、AIエージェントによる自動PR作成が普及しつつある現在のトレンドと合致する。GitHub公式ブランドの信頼性と、AI開発ワークフローへの適合性の両方が、本日のトレンド入りを後押ししたと推測される。

---
## 関連リンク

- https://github.com/github/gh-stack
- https://gh.io/stacks

---
## メモ
