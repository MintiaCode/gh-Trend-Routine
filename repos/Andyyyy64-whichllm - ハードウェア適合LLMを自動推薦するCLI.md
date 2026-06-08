---
url: https://github.com/Andyyyy64/whichllm
saved: 2026-06-08
tags:
  - python
  - trending
  - cli
  - ai
  - gpu
  - inference
  - benchmarks
  - command-line-tool
  - vram
  - huggingface
  - apple-silicon
  - llm
  - local-llm
  - ollama
  - gguf
category: GitHub Trending
status: 未読
rating:
---

# Andyyyy64/whichllm

▎ ハードウェア適合LLMを自動推薦するCLI

ライセンス: MIT
言語: Python
スター数: ⭐ 3400 (+103 今日)
トレンド順位: #10 (2026-06-08)

---
## 概要

whichllmは、ユーザーのGPU・CPU・RAM環境を自動検出し、その環境で実際に動作する最適なローカルLLMを推薦するコマンドラインツールです。単純にパラメータ数が大きいモデルを選ぶのではなく、LiveBench、Artificial Analysis、Aiderなどの実ベンチマーク結果を統合し、信頼性のあるスコアでランク付けします。NVIDIA、AMD、Apple Silicon、CPU専用環境に対応し、`uvx whichllm`一コマンドで即座に実行可能です。ハードウェアを購入前にGPUシミュレーションでモデル適合性を確認する機能もあり、ローカルLLMユーザーの「何を使えばいいか」という悩みを解決します。Python 3.11以上が必要で、`whichllm run`コマンドで推薦モデルとその場でチャットすることもできます。

---
## 主な機能・特徴

- ハードウェア自動検出 — NVIDIA/AMD/Apple Silicon/CPUを自動認識してVRAM・RAM制限を把握
- ベンチマーク統合ランキング — LiveBench・Artificial Analysis・Aider等の実測値でスコアリング
- GPU購入前シミュレーション — 仮想スペックを入力してモデル適合性を事前確認
- `whichllm run` — 推薦モデルとその場でインタラクティブチャットを開始
- Pythonコードスニペット生成 — 選択したモデルの統合コードを自動生成
- uvx/Homebrew/pip対応 — 複数インストール方法で環境を選ばない
- 信頼性グレーディング — 捏造ベンチマークや不当なスコア継承を積極的に排除

---
## トレンド入り理由の推測

ローカルLLMの普及とともに「自分のPC/MacにはどのLLMが最適か」という問いは多くのユーザーが直面する課題になった。VRAMの制限、GGUFのQuantization選択、Apple SiliconのUnified Memoryなど、選択肢が複雑化する中でワンコマンドで答えを出してくれるツールは実用性が高く、幅広いユーザーに訴求する。

v0.5.8が2026年6月5日にリリースされており、新機能の追加や改善がコミュニティに知られたことが今日のトレンド入りの直接的な要因と考えられる。Hacker NewsやRedditのr/LocalLLaMAなどのコミュニティでシェアされやすいツールの性質を持っており、「試してみた」という口コミが急速に広がりやすい。

「パラメータ数ではなく実ベンチマークで選ぶ」というアプローチは、LLM評価に疑問を感じていたユーザーにとって説得力があり、この訴求ポイントがバイラルな拡散を後押ししたと推測される。特にApple Siliconユーザーは高いUnified Memoryを活かせるモデルを探していることが多く、そのセグメントからの支持が大きいと考えられる。

---
## 関連リンク

- https://github.com/Andyyyy64/whichllm

---
## メモ

