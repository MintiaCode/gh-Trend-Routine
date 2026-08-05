---
url: https://github.com/cloudflare/computer
saved: 2026-08-05
tags:
  - typescript
  - trending
category: GitHub Trending
status: 未読
rating:
---

# cloudflare/computer

▎ AIエージェントに仮想PCを提供する基盤

ライセンス: MIT
言語: TypeScript
スター数: ⭐ 2500+ (+796 今日)
トレンド順位: #1 (2026-08-05)

---
## 概要

Cloudflare Computer は、Durable Object 内で動作する仮想ファイルシステムを核に、AIエージェントへ「使えるコンピュータ」を与えるためのプレビュー版基盤である。SQLiteに永続化された状態を唯一の真実の情報源とし、その上に差し替え可能な3種類の実行バックエンド — 実LinuxユーザランドをFUSEマウントする「Container」、Dynamic Worker上でjust-bashシェルを動かす「Isolate shell」、ECMAScriptモジュールを実行する「Isolate JavaScript」 — を選択的に接続できる設計になっている。`workspace.runtime.exec()` という単一のエントリポイントから、シェルコマンドでもJSモジュールでも同じ流儀で実行でき、バックエンドは初回利用時に遅延接続される。Cloudflare上でエージェント実行環境(computer use)を構築したい開発者や、コンテナとエッジWorkerを横断してAIエージェントに安全な作業領域を持たせたいチームが主な対象ユーザーとなる。現時点ではAPIが不安定なプレビュー段階であり、本番利用は非推奨とされている。

---
## 主な機能・特徴

- Durable Object上の仮想ファイルシステム — SQLiteを唯一の真実の情報源として永続化
- 3種類の実行バックエンド — Container / Isolate shell / Isolate JavaScript
- 統一実行API — `workspace.runtime.exec(source, { backend })` で一貫した呼び出し
- computerdデーモン — サンドボックス内でFUSEマウントし、capnweb RPCで状態を同期
- Node.js互換API — Workspace上でnode:fs/promisesがそのまま使える
- 豊富なサンプル集 — container/worker-shell/artifacts/assets等、用途別のexamplesを同梱
- モノレポ構成 — dofs / rpc / computerd / computer の各パッケージを個別公開
- プレビュー限定 — API変更前提、本番利用は非推奨と明記

---
## トレンド入り理由の推測

総スター数約2500に対し本日だけで796と、全体の3割以上を1日で獲得しており、リリース直後ないし大きな告知直後の急上昇と見られる。「エージェントにコンピュータを与える」というコンセプトは、AnthropicのComputer UseやOpenAIのOperatorなど2026年に入って加速している「AIエージェントに実行環境そのものを持たせる」潮流と直結しており、Cloudflareという大手エッジインフラ事業者がDurable Object・Workers・FUSEマウントを組み合わせて実装したことで、実運用に足る基盤として注目を集めていると考えられる。

また、Container/Isolate shell/Isolate JavaScriptという3種のバックエンドを同一APIで切り替えられる設計は、サンドボックス実行環境を自前構築していた開発者にとって魅力的であり、examplesディレクトリに用意されたAgentic Coding寄りのユースケース(ターミナル常駐エージェント、PDF生成、Artifacts公開等)が「すぐ試せる」訴求力を持っている点も、公開直後のスター急増を後押ししたと推測される。

---
## 関連リンク

- https://github.com/cloudflare/computer

---
## メモ
