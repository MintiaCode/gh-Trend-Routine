---
url: https://github.com/galilai-group/stable-worldmodel
saved: 2026-05-29
tags:
  - python
  - trending
  - deep-learning
  - pytorch
  - model-predictive-control
  - jepa
  - world-model
category: GitHub Trending
status: 未読
rating:
---

# galilai-group/stable-worldmodel

▎ 再現可能なワールドモデル研究評価プラットフォーム

ライセンス: 不明
言語: Python
スター数: ⭐ 1200 (+346 今日)
トレンド順位: #9 (2026-05-29)

---
## 概要

stable-worldmodelは、ワールドモデル研究の再現性と評価の統一化を目的としたオープンソース研究プラットフォームです。データ収集、モデルトレーニング、モデル予測制御（MPC）による評価という3段階のワークフローを統一的なAPIで提供します。DeepMind Control、ロボット操作、Atariゲームなど30以上の標準化された環境スイートを含み、Lance・HDF5・動画など複数のデータ形式に対応します。CEM（Cross-Entropy Method）などの計画ソルバーを7種類備え、DINO-WMやLeWMなどのベースライン実装も同梱されています。PyTorchベースで実装されており、pipによる簡単インストールで研究者がすぐに実験を開始できる設計です。

---
## 主な機能・特徴

- 統一ワークフロー — データ収集・訓練・評価を一貫したAPIで提供
- 30+標準環境 — DMControl、Atari、ロボット操作など多様なベンチマーク環境
- 多形式データ対応 — Lance・HDF5・動画など用途に応じたストレージ形式を選択可能
- 高速データロード — Lance形式でHDF5比3.4倍の処理速度（4814.8 vs 1416.1 samples/sec）
- 7種の計画ソルバー — サンプリング・勾配・制約付き最適化アプローチを網羅
- ベースライン実装 — DINO-WM・LeWMなどの参照実装を同梱
- CLIツール — コード不要でデータセット検査・変換が可能

---
## トレンド入り理由の推測

stable-worldmodelは2026年5月26日にバージョン0.1.0をリリースしたばかりであり、新規公開直後のトレンド入りです。合計1,200スターに対して本日346スターという急増は、AIコミュニティに即座に発見・注目されたことを示しています。ワールドモデルはDeepMind、OpenAI、FAIR（Meta AI）などが注力する分野であり、特にYann LeCun氏が推進するJEPA（Joint Embedding Predictive Architecture）への関心が高まる中、このリポジトリはJEPAをトピックに含むことで該当研究者の目に留まりやすい位置にあります。

再現可能性の欠如はAI研究の長年の課題であり、「reproducible」を前面に掲げた研究プラットフォームは学術コミュニティから強い支持を得やすい立場にあります。30以上の標準環境と統一評価フレームワークは、異なる研究グループ間の公正な比較を可能にし、研究加速への実用的な貢献として評価されています。

モデル予測制御（MPC）と深層学習の組み合わせはロボティクスや自動運転への応用が期待される分野であり、実用的なインパクトへの期待もスター増加に寄与しています。学術論文の公開やArXivへの掲載と同期してリリースされた可能性が高く、研究者コミュニティでのバイラル的な拡散がトレンド入りを後押ししたと考えられます。

---
## 関連リンク

- https://github.com/galilai-group/stable-worldmodel
- https://galilai-group.github.io/stable-worldmodel/

---
## メモ
