---
url: https://github.com/google-labs-code/design.md
saved: 2026-06-24
tags:
  - typescript
  - trending
category: GitHub Trending
status: 未読
rating:
---

# google-labs-code/design.md

▎ AIエージェント向けデザイン仕様形式

ライセンス: Apache-2.0
言語: TypeScript
スター数: ⭐ 17163 (+504 今日)
トレンド順位: #10 (2026-06-24)

---
## 概要

Googleが開発した、コーディングエージェントにビジュアルアイデンティティ（デザインシステム）を伝達するためのフォーマット仕様。YAML形式の機械可読なデザイントークン（色、タイポグラフィ、スペーシング、コンポーネント定義）とMarkdown形式の人間可読な設計根拠を一つのファイルに統合する。エージェントはこのファイルを読み込むことで、プロジェクトのデザインシステムを永続的・構造的に理解し、一貫したUIを生成できるようになる。CLIツールとしてlint（構造検証）、diff（バージョン比較）、export（Tailwind/W3C DTCG形式への変換）機能を提供。WCAGコントラスト比チェック、参照整合性、セクション順序など9つの自動チェックルールを搭載。現在アルファ版として活発に開発中。

---
## 主な機能・特徴

- YAML+Markdown統合 — デザイントークンと設計根拠を一ファイルに
- 色・タイポグラフィ・間隔 — hex/rgb/oklch、フォント属性のトークン定義
- トークン参照構文 — {path.to.token}でトークン間の参照が可能
- lint機能 — WCAG準拠チェック含む9ルールの自動検証
- diff機能 — バージョン間のデザインリグレッション検出
- export機能 — Tailwind JSON/CSS、W3C DTCG形式への変換
- エージェント理解 — AIコーディングエージェントにデザイン文脈を提供

---
## トレンド入り理由の推測

Google Labs発のプロジェクトとして、AIエージェント×デザインシステムという新しい交差領域を定義した先駆的な仕様である。17163スター、今日+504スターと非常に高い注目度を示している。AIコーディングエージェントが生成するUIの品質が課題として認識される中、デザインの一貫性を機械可読な形で担保するアプローチは業界全体の痛点に対応している。

Cursor、Claude Code、Copilotなど各種AIコーディングツールが「見た目の良いUI」を生成する需要に応える規格として、フロントエンド開発者とデザイナーの両方から注目を集めている。Tailwindへのエクスポート対応が実用性を高め、Google Stitchプラットフォームとの連携も含めてGoogleのエージェントエコシステム戦略の一端として関心が集まっている。

---
## 関連リンク

- https://github.com/google-labs-code/design.md
- https://stitch.withgoogle.com/docs/design-md/specification

---
## メモ
