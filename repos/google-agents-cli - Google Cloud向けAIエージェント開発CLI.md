---
url: https://github.com/google/agents-cli
saved: 2026-06-30
tags:
  - python
  - trending
  - adk
  - agent-development-kit
  - agents
  - coding-agent
  - gemini
  - gemini-enterprise-agent-platform
  - generative-ai
  - google-cloud
category: GitHub Trending
status: 未読
rating:
---

# google/agents-cli

▎ Google Cloud向けAIエージェント開発CLI

ライセンス: Apache-2.0
言語: Python
スター数: ⭐ 4090 (+433 今日)
トレンド順位: #10 (2026-06-30)

---
## 概要

agents-cliは、Claude Code・Codex・Antigravity CLIなど任意のコーディングアシスタントに「スキル」を追加し、Google CloudのGemini Enterprise Agent Platform上でエージェントを構築・評価・デプロイ・運用できるようにするCLIツールである。開発者が個々のクラウドサービスやAPIを逐一学習しなくても、コーディングエージェントに知識（スキル）を与えることでエージェント開発のライフサイクル全体（スキャフォールディング、ADKによるコード実装、評価指標・LLM-as-judgeによる評価、Cloud Run/GKEへのデプロイ、Gemini Enterpriseへの登録、Cloud Traceによる可観測性確保）を自動化・効率化する点が特徴である。エンタープライズ規模のAIエージェントを構築したい開発者、特にGoogle Cloud上でのプロダクション運用を見据えたチームを主な対象としており、`uvx google-agents-cli setup`または`npx skills add google/agents-cli`の一行コマンドで導入できる手軽さも魅力である。

---
## 主な機能・特徴

- スキル形式の知識付与 — Claude Code等のコーディングエージェントにADK/評価/デプロイ知識を追加
- プロジェクトスキャフォールディング — agents-cli scaffoldで新規エージェントプロジェクトを生成
- 評価パイプライン — eval generate/gradeでLLM-as-judgeによる多面的評価が可能
- 自動プロンプト最適化 — eval optimizeで評価データを基にプロンプトを自動調整
- マルチデプロイ対応 — Agent Runtime/Cloud Run/GKEへのデプロイをサポート
- Gemini Enterprise登録 — publish gemini-enterpriseでエンタープライズ環境に公開
- CI/CD・インフラ自動構築 — infra cicdでステージング/本番環境を一括整備
- 観測性統合 — Cloud Traceやログ連携で運用監視を強化

---
## トレンド入り理由の推測

本リポジトリはpushed_atが2026-06-28と直近で活発に更新されており、Googleという大手ベンダーが「コーディングエージェントを強化するスキル配布」という新しいモデルを公式に推進している点が433スターという急増の主因と考えられる。Claude Code・Codex・Antigravityなど複数の主要コーディングエージェントを横断的にサポートする姿勢は、特定ベンダーロックインを避けたい開発者から好意的に受け止められやすい。

また、「コーディングエージェント＋スキル＋エンタープライズクラウド」という組み合わせは、2026年前半における生成AIエージェント開発の中心的トレンドそのものであり、Google Cloud上でのエージェント本番運用（評価・デプロイ・観測性まで一貫してCLIでカバー）という実用性の高さが、企業の開発チームやMLOpsエンジニアからの関心を集めたとみられる。npx skills addという極めてシンプルな導入手順も、試しやすさからバイラルな拡散を後押しした可能性が高い。

---
## 関連リンク

- https://github.com/google/agents-cli
- https://google.github.io/agents-cli/

---
## メモ
