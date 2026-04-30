---
url: https://github.com/Alishahryar1/free-claude-code
saved: 2026-04-27
tags:
  - python
  - trending
category: GitHub Trending
status: 未読
rating:
---

# Alishahryar1/free-claude-code

▎ Claude Codeを無料で使うプロキシツール

ライセンス: MIT
言語: Python
スター数: ⭐ 15954 (+2,973 今日)
トレンド順位: #4 (2026-04-27)

---
## 概要

本リポジトリは、Anthropic APIキーなしでClaude Code CLIおよびVSCode拡張機能を無料で使用するための軽量プロキシツールです。Claude CodeのAnthropicへのAPIコールをNVIDIA NIM（無料で毎分40リクエスト）、OpenRouter（多数の無料モデル）、DeepSeek、LM Studio、llama.cpp、Ollamaなど6種類のプロバイダーにルーティングします。環境変数を2つ設定するだけで動作し、Claude Code本体への変更は不要です。Thinking Token対応、モデルごとのプロバイダー振り分け、スマートなレート制限、さらにDiscord/TelegramボットによるリモートAIコーディングまで多機能を備えており、コストゼロでClaude Codeの能力を最大限活用したい開発者向けのツールです。

---
## 主な機能・特徴

- NVIDIA NIM（無料）、OpenRouter、DeepSeek、LM Studio、llama.cpp、Ollamaの6プロバイダー対応
- 環境変数2つを設定するだけのドロップイン置き換え設計
- Opus/Sonnet/Haikuを異なるモデル・プロバイダーへルーティング可能
- `<think>`タグ・reasoning_contentをClaude思考ブロックに変換するThinking Token対応
- テキストとして出力されるツールコールを自動パースするHeuristic Tool Parser
- スマートレート制限（ローリングウィンドウスロットル＋429指数バックオフ）
- Discord/TelegramボットによるリモートAIコーディング（ツリー型スレッド管理）
- `BaseProvider`抽象クラスで新プロバイダーを簡単追加可能な拡張性

---
## トレンド入り理由の推測

本日2,973スターという爆発的な増加は、Claude Codeの有料プランへの敷居の高さへの反発と、「無料で使いたい」という開発者需要が完全にマッチした結果です。Anthropic APIは従量課金制でコストが発生するため、学生や個人開発者・探索的ユーザーにとって大きなハードルとなっています。このツールはその障壁を実質的に取り除くことで、広範な開発者層に訴求しています。

NVIDIA NIMが毎分40リクエスト無料という具体的な「タダで使える」ソリューションを提示している点と、LM Studio・Ollamaなどのローカル実行オプションも揃えていることで、プライバシー重視派・コスト重視派の双方を取り込んでいます。pushed_atが前日（2026-04-26）の深夜に更新されており、直前の安定版リリースがSNSで拡散した可能性が高いです。

また、mattpocock/skillsやComposioHQ/awesome-codex-skillsが同日トレンド上位に入るなど「Claude Code関連リポジトリ」全体への注目が高まる中、「無料で使える」という検索ニーズに応えるキーワードが機能し、連鎖的にディスカバリーされたと考えられます。

---
## 関連リンク

- https://github.com/Alishahryar1/free-claude-code

---
## メモ

