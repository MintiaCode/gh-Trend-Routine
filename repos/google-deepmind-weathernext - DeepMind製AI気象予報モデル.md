---
url: https://github.com/google-deepmind/weathernext
saved: 2026-08-09
tags:
  - python
  - trending
  - weather
  - weather-forecast
category: GitHub Trending
status: 未読
rating:
---

# google-deepmind/weathernext

▎ DeepMind製AI気象予報モデル

ライセンス: Apache-2.0
言語: Python
スター数: ⭐ 7000 (+105 今日)
トレンド順位: #5 (2026-08-09)

---
## 概要

WeatherNextは、Google DeepMindとGoogle Researchが開発する、地球規模の中期気象予報および台風・サイクロン予測を行うAIモデル群です。従来の数値気象予測(NWP)に代わる、あるいは補完するアプローチとして、機械学習ベースの予測モデルを提供しており、現行世代の「WeatherNext 2」では0.25度(約30km)の解像度でグローバルな中期気象予報と100m風速を含む標準的な気象変数を予測できます。前世代にあたるグラフニューラルネットワークベースの「GraphCast」や拡散モデルベースのアンサンブル予測手法「GenCast」も含め、複数世代のモデルが公開されています。予報データはGoogle Cloud(Earth Engine、BigQuery、Vertex AI)やOpenMeteoのAPIなど複数のプラットフォームからアクセス可能で、Colabノートブックによるハンズオンも用意されており、軽量な「Mini」版は無料のColab TPUアクセラレータでも動作します。気象研究者、データサイエンティスト、気象データを活用したいアプリケーション開発者などが主な対象ユーザーです。

---
## 主な機能・特徴

- 高解像度グローバル予報 — 0.25度(約30km)解像度で中期気象・台風予測が可能
- 複数世代のモデル提供 — 最新のWeatherNext 2に加え、GraphCast・GenCastも公開
- マルチプラットフォーム提供 — Google Cloud(Earth Engine, BigQuery, Vertex AI)やOpenMeteo APIから利用可能
- Colabノートブック — モデル読み込み・推論・可視化を体験できるハンズオン環境
- 軽量版モデル — Mini版は無料のColab TPU/P100 GPUでも動作
- 事前学習済み重み配布 — Google Cloud Storageから学習済みモデルと サンプルデータを取得可能
- オープンライセンス — コードはApache 2.0、その他の成果物はCC BY 4.0で公開

---
## トレンド入り理由の推測

WeatherNextは本日105スターを獲得しており、Google DeepMindという知名度の高い組織が手がける気象予測AIという点が継続的な注目を集めている背景にあると考えられます。気象予測は防災・農業・エネルギー・保険など幅広い産業に直結する応用分野であり、AIモデルが従来の数値予報を上回る精度・速度を達成しつつあるという近年の研究動向(GraphCastやGenCastの学術的成果を含む)が、実務者・研究者双方からの関心を継続的に呼んでいると推測されます。

またリポジトリの構成上、複数世代のモデル(WeatherNext 2、GenCast、GraphCast)が一つのプロジェクトとしてまとまっており、Google Cloud上でのデータ提供やOpenMeteoとの連携など実運用を意識したエコシステムが整っている点も、単なる研究デモに留まらない実用性の高さとして評価され、GitHub Trendingで安定した支持を得ている一因と考えられます。

---
## 関連リンク

- https://github.com/google-deepmind/weathernext

---
## メモ
