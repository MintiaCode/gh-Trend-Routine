---
url: https://github.com/presenton/presenton
saved: 2026-05-23
tags:
  - typescript
  - trending
  - api
  - presentation
  - gamma
  - powerpoint-generation
  - powerpoint-automation
  - ai-agent
  - powerpoint-free
  - ai-presentation
category: GitHub Trending
status: 未読
rating:
---

# presenton/presenton

▎ オープンソースAIプレゼン自動生成ツール

ライセンス: Apache-2.0
言語: TypeScript
スター数: ⭐ 6300 (+335 今日)
トレンド順位: #10 (2026-05-23)

---
## 概要

PrestonはAIを活用したオープンソースのプレゼンテーション生成ツールで、有料SaaSサービス「Gamma」「Beautiful.AI」「Decktopus」の代替として注目を集めている。ユーザーはOpenAI、Google Gemini、Anthropic Claude、Azure OpenAI、Amazon Bedrockなど多様なLLMプロバイダーを自由に選択でき、Ollamaを通じたローカルモデルにも対応している。デスクトップアプリ（macOS・Windows・Linux）とDockerコンテナによるセルフホスト型展開が可能で、データの完全なコントロールを手元に保ちながら高品質なプレゼンを作成できる。PowerPoint（PPTX）とPDF形式でのエクスポート、HTMLとTailwind CSSを使ったカスタムテンプレート作成、MCPサーバー連携にも対応しており、AIエージェントからの直接利用も視野に入れた設計となっている。バックエンドはFastAPI、フロントエンドはNext.jsという人気スタックを採用し、開発者の参入障壁が低い。

---
## 主な機能・特徴

- マルチLLM対応 — OpenAI、Claude、Gemini、Azure、Bedrock等あらゆるLLMプロバイダーを選択可能
- セルフホスト対応 — Docker、デスクトップアプリ、Railway・DigitalOceanへの柔軟なデプロイ
- PPTX/PDFエクスポート — PowerPointおよびPDF形式での高品質なプレゼン出力
- カスタムテンプレート — HTMLとTailwind CSSで独自スライドテンプレートを作成可能
- REST API提供 — `/api/v1/ppt/presentation/generate`で自動化・エージェント組み込みが容易
- MCPサーバー対応 — AIエージェントとのシームレスな統合をサポート
- プレゼンメモリ機能 — Mem0 OSSを活用したコンテキスト保持で継続的な改善が可能

---
## トレンド入り理由の推測

Gammaをはじめとする有料AIプレゼンツールへの依存に不満を持つ開発者・ビジネスユーザーが多い中、「完全オープンソース・セルフホスト可能」という選択肢への需要が高まっていることが最大の背景にある。特にデータプライバシーや社内機密情報の外部送信を避けたい企業にとって、ローカル展開対応は大きな訴求点となっており、エンタープライズ市場への訴求力が従来の類似ツールと一線を画している。

また、Claude Code / MCPエコシステムの広がりとともに「AIエージェントから直接プレゼンを生成する」ユースケースへの関心が高まっており、MCPサーバー対応をいち早く実装したことが開発者コミュニティの注目を集めているタイミングと合致した。今後、AIによる資料作成の自動化フローに組み込まれるツールとしての需要が急増していることが読み取れる。

6,300スターに対して335スター増という比率は、新規ユーザーの急増を示している。TypeScriptとFastAPIという人気技術スタックの組み合わせが開発者の参入障壁を下げており、fork数1,100超という数字からも実際に自分のプロジェクトに組み込もうとする開発者が多いことが窺える。ProductHuntやHacker Newsへのポスト、もしくはYouTubeデモ動画の拡散が今回のスパイクの引き金になったと推測される。

---
## 関連リンク

- https://github.com/presenton/presenton
- https://presenton.ai

---
## メモ
