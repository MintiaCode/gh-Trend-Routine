---
url: https://github.com/huggingface/speech-to-speech
saved: 2026-07-28
tags:
  - python
  - trending
  - ai
  - assistant
  - language-model
  - machine-learning
  - speech
  - speech-synthesis
  - speech-to-text
  - speech-translation
category: GitHub Trending
status: 未読
rating:
---

# huggingface/speech-to-speech

▎ ローカル音声対話AIパイプライン

ライセンス: Apache-2.0
言語: Python
スター数: ⭐ 7100 (+177 今日)
トレンド順位: #6 (2026-07-28)

---
## 概要

speech-to-speechは、Hugging Faceが開発するオープンソースの音声対話パイプラインで、VAD（音声区間検出）→ STT（音声認識）→ LLM（大規模言語モデル）→ TTS（音声合成）という4段階のモジュール構成を採用しています。各コンポーネントは独立したスレッドでキューを介して接続され、OpenAI Realtime API互換のWebSocketインターフェースを提供するため、既存のOpenAIリアルタイム音声アプリケーションとの互換性を保ちながら、完全にローカルまたは自己ホスト環境で音声エージェントを構築できます。

VADにはSilero VAD v5、STTにはParakeet TDTをデフォルトとしつつWhisper系やFaster Whisper、Paraformerなど複数バックエンドを選択可能。LLMはOpenAI互換API、ローカルTransformers、Apple SiliconのMLX-LM、vLLMやllama.cppといった自己ホストサーバーに対応し、TTSはQwen3-TTSをデフォルトにKokoroやPocket TTSなども選べます。Realtime・Local・WebSocket・Socketの4つの動作モードを持ち、マイク直結の常駐エージェントからリモートサーバー向けPCMストリーミングまで幅広いユースケースに対応します。ターゲットユーザーはプライバシー重視でクラウドAPIに依存しない音声アシスタントを構築したい開発者や、ロボティクス分野で音声対話を実装したいエンジニアです。

---
## 主な機能・特徴

- VAD→STT→LLM→TTSの4段階モジュール型音声パイプライン
- OpenAI Realtime API互換のWebSocketサーバーを標準提供
- Parakeet TDT・Whisper・Faster Whisper・Paraformerなど複数STTバックエンド対応
- ローカルTransformers・MLX-LM・vLLM・llama.cppなど柔軟なLLMバックエンド選択
- Qwen3-TTSやKokoro、Pocket TTSなど複数TTSバックエンドをサポート
- Realtime・Local・WebSocket・Socketの4種類のデプロイモード
- 25以上の言語に対応する多言語音声認識・合成
- 数千台のReachy Miniロボットの会話バックエンドとして本番運用中

---
## トレンド入り理由の推測

huggingface/speech-to-speechは、Hugging FaceというAI業界で高い信頼性を持つ組織が公開しているリポジトリであり、累計7,100スターに対して1日で177スターという着実な増加を見せています。急激なバズというより、Hugging Faceブランドへの継続的な注目と、ローカルで動く音声AIへの需要の高まりが背景にあると考えられます。

技術的には、OpenAI Realtime API互換という設計判断が大きな注目点です。多くの開発者がすでにOpenAIのリアルタイム音声APIに慣れているため、同じインターフェースでローカル・自己ホスト環境に切り替えられる点は、コスト削減やデータプライバシーを重視する企業・開発者にとって強い訴求力を持ちます。また「数千台のReachy Miniロボットで本番運用中」という実績が示され、ホビイストからロボティクス企業まで実用的な採用が進んでいることも話題性を高めています。

音声AIエージェント分野は2025〜2026年にかけてLLMエコシステムの中でも特に成長が著しい領域であり、VAD・STT・LLM・TTSの各要素を柔軟に組み合わせられるモジュール設計は、特定用途に合わせたカスタマイズを求める開発者コミュニティから継続的な関心を集めやすい構造になっています。

---
## 関連リンク

- https://github.com/huggingface/speech-to-speech

---
## メモ
