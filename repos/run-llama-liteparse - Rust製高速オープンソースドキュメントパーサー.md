---
url: https://github.com/run-llama/liteparse
saved: 2026-05-29
tags:
  - rust
  - trending
  - pdf
  - ocr
  - text-extraction
  - ocr-recognition
  - pdf-parser
  - document-processing
  - document-ocr
category: GitHub Trending
status: 未読
rating:
---

# run-llama/liteparse

▎ Rust製高速オープンソースドキュメントパーサー

ライセンス: Apache-2.0
言語: Rust
スター数: ⭐ 7100 (+680 今日)
トレンド順位: #8 (2026-05-29)

---
## 概要

LiteParseは、LlamaIndexチームが開発した高速・軽量なオープンソースのドキュメントパーサーです。PDF、DOCX、XLSX、PPTX、画像など多様な形式に対応し、空間的なテキスト抽出とバウンディングボックス付きの構造化JSONを出力します。クラウド依存なしに完全ローカルで動作し、Rust、Node.js/TypeScript、Python、WebAssembry（ブラウザ）の各環境から利用できます。OCR機能はTesseractが組み込み済みでゼロセットアップで動作するほか、EasyOCR・PaddleOCRとのHTTP連携や完全無効化も選択可能です。Linux、macOS（Intel/ARM）、Windowsを全てサポートし、RAGパイプラインやLLMエージェント向けのドキュメント前処理ツールとして設計されています。

---
## 主な機能・特徴

- 多形式対応 — PDF・DOCX・XLSX・PPTX・画像を統一APIで処理
- 空間テキスト抽出 — バウンディングボックス付き構造化JSONを出力
- ローカル完結動作 — クラウド依存なし、完全オフライン処理が可能
- マルチ言語バインディング — Rust・Python・Node.js・WASMで利用可能
- 柔軟なOCR対応 — Tesseract組み込み、HTTP連携、カスタムAPI対応
- LLMエージェント向け — PNG スクリーンショット出力でビジョンLLMとの連携も支援
- 高速処理 — Rustによる高パフォーマンス実装でバッチ処理に適する

---
## トレンド入り理由の推測

LiteParseは2026年5月28日にDocker v2.0.3をリリースしたばかりであり、新バージョンリリース直後のトレンド入りというパターンです。680スターという本日の獲得数は合計7,100スターの約10%に相当し、リリースによる急激なスパイクが確認できます。RAGシステムやLLMエージェントのパイプラインにおいて、ドキュメントパーシングは品質を左右する重要なステップであり、高速・ローカル動作・オープンソースという三拍子揃ったツールへの需要は非常に高まっています。

特にRust製であることが開発者の関心を引いています。Python製のパーサーが多い中、Rustによる実装は処理速度と安全性で優位性を持ち、大量ドキュメントのバッチ処理が必要な本番環境での採用に適しています。またPython・Node.js・WASMへのバインディングを完備しているため、Rustを直接書けない開発者でも恩恵を受けられる設計も高評価です。

LlamaIndex（旧GPT Index）はRAG・LLMエコシステムの中心的フレームワークであり、そのチームが開発したオープンソースツールは自然とコミュニティの信頼を得やすい環境にあります。クラウド版LlamaParseの無料代替として使える点もスター増加を後押ししており、AI/LLMエコシステムにおけるオープンソース志向の高まりを反映しています。

---
## 関連リンク

- https://github.com/run-llama/liteparse
- https://developers.llamaindex.ai/liteparse/

---
## メモ
