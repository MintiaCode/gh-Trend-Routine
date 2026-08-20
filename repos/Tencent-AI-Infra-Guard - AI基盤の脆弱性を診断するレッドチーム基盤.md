---
url: https://github.com/Tencent/AI-Infra-Guard
saved: 2026-08-20
tags:
  - go
  - trending
  - agent
  - agent-security
  - ai-infra
  - ai-red-teaming
  - ai-security
  - llm
  - llm-evaluation
  - llm-jailbreak
  - llm-security
  - mcp-scan
  - prompt-injection
  - prompt-security
  - scanner
  - security
  - security-tools
  - skill-scanner
  - vulnerability
category: GitHub Trending
status: 未読
rating:
---

# Tencent/AI-Infra-Guard

▎ AI基盤の脆弱性を診断するレッドチーム基盤

ライセンス: Apache-2.0
言語: Go
スター数: ⭐ 4900 (+28 今日)
トレンド順位: #16 (2026-08-20)

---
## 概要

AI-Infra-Guard は、Tencent 朱雀ラボ(Zhuque Lab)が開発する、AI エコシステム全体を対象としたフルスタックのレッドチーム評価プラットフォームである。単一の脆弱性スキャナではなく、AI インフラの CVE 診断、エージェントのセキュリティ評価、MCP サーバーと Agent Skills の監査、そして脱獄(Jailbreak)耐性テストという複数の観点を一つの基盤に統合している点が特徴である。

LLM を組み込んだシステムが本番投入される段階に入り、攻撃面は従来のアプリケーションとは別物になった。プロンプトインジェクション、悪意ある MCP サーバー、細工されたスキル定義、多段会話による安全機構の回避といった脅威は、既存の Web 脆弱性スキャナでは検出できない。一方でこれらを個別のツールで検査すると、評価が断片化して全体像がつかめなくなる。AI-Infra-Guard はこの断絶を、統合プラットフォームという形で埋めようとしている。

実装面では、100 種類以上の AI フレームワーク component に対する 2000 以上の CVE ルール、Dify や Coze といったエージェントプラットフォームに対応するマルチエージェント自動評価フレームワーク、14 分類のリスクと SkillTrustBench T01〜T09 の脅威分類に基づくスキル/MCP 監査、Many-Shot・PAIR・GOAT・ActorAttack といった手法を用いた多段脱獄評価を備える。YAML でフィンガープリントルールを追加できるプラグイン機構、skill-scan / mcp-scan / agent-scan の単体 CLI、Docker Compose による配備、そしてリアルタイムに進捗を表示する Web UI が用意されている。評価モデルは Claude・DeepSeek・Gemini・GLM・Kimi など複数に対応し、特定ベンダーに依存しない。

---
## 主な機能・特徴

- AI インフラ脆弱性スキャン — 100+ のフレームワーク component に対し 2000+ の CVE ルールで診断
- エージェント評価 — Dify / Coze 等のプラットフォーム上のエージェントをマルチエージェントで自動検査
- Skills / MCP 監査 — 14 分類のリスクと SkillTrustBench T01〜T09 の脅威分類に沿って検出
- 脱獄耐性評価 — Many-Shot・PAIR・GOAT・ActorAttack による多段攻撃シナリオを実行
- プラグイン拡張 — YAML でフィンガープリントルールと脆弱性データセットを追加可能
- 単体 CLI — skill-scan / mcp-scan / agent-scan を個別に CI へ組み込める
- モデル非依存 — Claude・DeepSeek・Gemini・GLM・Kimi など複数モデルを評価エンジンに選択可能
- Docker 配備と Web UI — Compose 一発で起動し、進捗と結果をブラウザで確認

---
## トレンド入り理由の推測

今日 +28 スターは、総スター 4,900 に対して小さな数字である。急騰型ではなく、地道に積み上げてきたプロジェクトがトレンド枠の下位に顔を出した形と見るのが妥当だろう。ただし、この規模のスターを持つセキュリティツールがトレンドに載ること自体、AI セキュリティという領域の裾野が広がっている証拠でもある。

直接のきっかけとして考えられるのは、v4.5.2 が 8 月 17 日にリリースされたばかりという点である。トピックに openclaw-security・skills-security・skill-scanner が並んでいることから、直近の更新は「エージェントスキル」の監査機能に重心があると推測できる。スキル配布が一般化するにつれ、サードパーティのスキル定義や MCP サーバーを無検査で読み込むリスクが現実の懸念として認識され始めており、それを検査する側のツールに需要が生まれている。

もう一つの要因は開発元である。Tencent という大手が公式に AI レッドチーミング基盤を公開していることは、企業のセキュリティチームにとって導入検討の心理的ハードルを大きく下げる。個人開発の実験的ツールでは社内展開しにくいが、大手ラボ発かつ Apache-2.0 であれば話が別になる。エージェントを本番投入する企業が増えるほど「デプロイ前に何かで検査したい」という需要は増えるため、この種の統合プラットフォームは今後も緩やかに伸び続ける可能性が高い。

---
## 関連リンク

- https://github.com/Tencent/AI-Infra-Guard
- https://tencent.github.io/AI-Infra-Guard/

---
## メモ

