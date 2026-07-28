---
url: https://github.com/microsoft/agent-governance-toolkit
saved: 2026-07-28
tags:
  - python
  - trending
  - agent-framework
  - ai-agents
  - ai-safety
  - compliance
  - governance
  - microsoft
  - owasp
  - policy-engine
  - security
  - trust
  - zero-trust
category: GitHub Trending
status: 未読
rating:
---

# microsoft/agent-governance-toolkit

▎ AIエージェント向けゼロトラスト統治基盤

ライセンス: MIT
言語: Python
スター数: ⭐ 5100 (+17 今日)
トレンド順位: #10 (2026-07-28)

---
## 概要

Agent Governance Toolkit（AGT）は、Microsoftが公開する自律型AIエージェント向けのポリシー実施・ゼロトラストID管理・実行サンドボックス化・監査ログ基盤です。プロンプトレベルでの安全対策を「確率的システムへの丁寧なお願い」に過ぎないと位置づけ、代わりにアプリケーション層での決定論的な制御を実装します。ドキュメントでは「AGTカーネルが拒否したアクションは『起こりにくい』のではなく『構造的に不可能』である」と強調されており、権限管理・エージェント特定・監査可能性という3つの課題に対処します。

利用は非常にシンプルで、既存のツール関数を`govern()`でラップしてポリシーYAMLを指定するだけで導入できます。Python実装が最も充実していますが、TypeScript・.NET・Rust・Goでも実装が存在し、OpenAI Agents SDK・CrewAI・LangChain・Semantic Kernelなど主要エージェントフレームワークとの統合も提供します。OWASP Agentic AI Top 10やNIST AI RMF 1.0、EU AI Act、SOC 2といったコンプライアンス基準にマッピングされ、10の正式仕様に対して992のコンフォーマンステストを備えています。ターゲットユーザーは、本番環境で自律型AIエージェントを安全に運用したいエンタープライズ開発者やセキュリティ担当者です。

---
## 主な機能・特徴

- ツール関数を2行でラップするだけのシンプルなガバナンス導入
- ポリシーYAMLによる宣言的なアクション許可・拒否制御
- ゼロトラストなエージェントID管理と実行サンドボックス化
- 改ざん耐性を持つ監査ログによる説明責任の担保
- Python・TypeScript・.NET・Rust・Goのマルチ言語実装
- OpenAI Agents SDK・CrewAI・LangChain・Semantic Kernel等との統合
- OWASP Agentic AI Top 10・NIST AI RMF・EU AI Actへの準拠マッピング
- 10仕様・992コンフォーマンステストによる品質保証

---
## トレンド入り理由の推測

microsoft/agent-governance-toolkitはMicrosoftという大手テック企業が公開したリポジトリであることに加え、公式ホームページ（microsoft.github.io）まで整備された本格的なプロジェクトです。1日17スターの増加は他の急上昇リポジトリと比べ緩やかですが、公開から着実に注目を集めている段階にあると考えられ、企業のAIガバナンス担当者やセキュリティエンジニアからの継続的な関心がうかがえます。

技術的には「AIエージェントの自律実行に伴うセキュリティリスク」というまさに2025〜2026年のホットトピックに正面から取り組んでいる点が大きいです。プロンプトインジェクションや意図しないツール実行など、自律エージェントの実運用で懸念される問題に対し、プロンプトではなくアプリケーション層での決定論的制御という具体的な解決策を提示していることが、実務者の関心を引いています。

さらにOWASP Agentic AI Top 10やEU AI Actといった規制・標準への準拠を明記している点は、エンタープライズでのAIエージェント導入が本格化する中、コンプライアンス要件を満たす必要のある企業にとって直接的な採用理由となり、今後さらに評価が広がる可能性があります。

---
## 関連リンク

- https://github.com/microsoft/agent-governance-toolkit
- https://microsoft.github.io/agent-governance-toolkit

---
## メモ
