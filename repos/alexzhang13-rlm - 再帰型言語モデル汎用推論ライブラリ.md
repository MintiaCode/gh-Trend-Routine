---
url: https://github.com/alexzhang13/rlm
saved: 2026-06-17
tags:
  - python
  - trending
  - recursive-language-models
  - inference
  - ai
  - machine-learning
category: GitHub Trending
status: 未読
rating:
---

# alexzhang13/rlm

▎ 再帰型言語モデル汎用推論ライブラリ

ライセンス: MIT
言語: Python
スター数: ⭐ 4900 (+37 今日)
トレンド順位: #19 (2026-06-17)

---
## 概要

rlmは、再帰型言語モデル（Recursive Language Models / RLMs）のための汎用プラグアンドプレイ推論ライブラリである。RLMsは、言語モデルが入力をプログラム的に検査・分解し、自分自身を再帰的に呼び出すことで、ほぼ無限長のコンテキストを処理するタスク非依存型の推論パラダイムを実現する。ローカル実行、IPython、Docker、Modal、Prime Intellect、Daytona、E2Bなど多様なREPL環境（サンドボックス）をサポートし、複数のモデルプロバイダーと連携可能。Prime Intellectのフレームワークを用いた学習機能も提供しており、DSPy、Ax、context-labsなど様々な組織での本番利用実績がある。

---
## 主な機能・特徴

- 再帰的自己呼び出し — LMが自身を再帰的に呼び出し無限長コンテキストを処理
- タスク非依存設計 — 特定タスクに依存しない汎用的な推論パラダイム
- マルチサンドボックス対応 — ローカル、Docker、Modal、E2Bなど7種のREPL環境
- プラグアンドプレイ — 既存のモデルに簡単に統合可能な設計
- マルチプロバイダー — 複数のLLMプロバイダーをサポート
- 学習機能 — Prime Intellectフレームワークによるモデル学習に対応
- 本番運用実績 — DSPy等の主要フレームワークでの採用実績あり

---
## トレンド入り理由の推測

RLMsがトレンド入りしている背景には、LLMのコンテキスト長制限という根本的課題に対する新しいアプローチへの関心がある。従来のRAGやコンテキスト圧縮とは異なり、モデル自身が再帰的に入力を分解・処理するという概念は、AIエージェントの自律性向上の文脈で非常に注目されている。

arXivの論文とブログポストの公開に伴い、学術コミュニティと実務者の両方から関心が集まっている。特にDSPyやAxといった既に広く使われているフレームワークでの本番利用実績が信頼性を裏付けており、研究段階から実用段階への移行を示している。

AIエージェントが長大なコードベースやドキュメントを処理する際の基盤技術として、再帰的推論の可能性に開発者コミュニティが注目しており、今後のLLMアプリケーション設計に影響を与える可能性のある技術として話題になっている。

---
## 関連リンク

- https://github.com/alexzhang13/rlm
- https://arxiv.org/abs/2512.24601
- https://alexzhang13.github.io/blog/2025/rlm/
- https://alexzhang13.github.io/rlm/

---
## メモ
