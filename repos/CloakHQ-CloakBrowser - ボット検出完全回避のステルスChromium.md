---
url: https://github.com/CloakHQ/CloakBrowser
saved: 2026-05-10
tags:
  - python
  - trending
  - ai-agents
  - anti-detect
  - antidetect-browser
  - bot-detection
  - browser-automation
  - captcha-bypass
  - chromium
  - cloudflare
  - cloudflare-bypass
  - fingerprint
  - headless-browser
  - playwright
  - puppeteer
  - python
  - recaptcha
  - selenium
  - stealth-browser
  - undetected
  - web-scraping
  - webscraping
category: GitHub Trending
status: 未読
rating:
---

# CloakHQ/CloakBrowser

▎ ボット検出完全回避のステルスChromium

ライセンス: MIT
言語: Python
スター数: ⭐ 4523 (+567 今日)
トレンド順位: #4 (2026-05-10)

---
## 概要

CloakBrowserは、あらゆるボット検出テストをパスするステルスChromiumブラウザです。JSインジェクションや設定パッチではなく、C++ソースレベルでフィンガープリントを修正した本物のChromiumバイナリを提供します。Canvas、WebGL、音声、フォント、GPU、スクリーン、WebRTC、ネットワークタイミング、自動化シグナルなど49箇所のソースレベルパッチにより、アンチボットシステムから通常のブラウザとして認識されます。PlaywrightおよびPuppeteerのドロップイン置き換えとして設計されており、importを3行変更するだけで既存コードがそのまま動作します。PythonとJavaScript両方をサポートし、`pip install cloakbrowser`または`npm install cloakbrowser`で即座に利用開始できます。Cloudflare Turnstile、FingerprintJS、BrowserScanなど30以上の検出サイトでのテストをパスしており、reCAPTCHA v3スコア0.9を達成しています。

---
## 主な機能・特徴

- C++ソースレベル49箇所パッチ — Canvas/WebGL/音声/GPU/WebRTCなどフィンガープリントを根本から偽装
- humanize=Trueフラグ — 人間らしいマウスカーブ・キーボードタイミング・スクロールパターンをワンフラグで有効化
- reCAPTCHA v3スコア0.9達成 — サーバー検証で人間レベルのスコアを実現
- Playwright/Puppeteer完全互換 — import変更3行で既存コードをそのまま流用可能
- 自動更新バイナリ — バックグラウンドで常に最新ステルスビルドへ自動更新
- ブラウザプロファイルマネージャー — Multilogin/GoLoginの自己ホスト代替、noVNCでブラウザ管理
- Dockerワンコマンド試用 — `docker run --rm cloakhq/cloakbrowser cloaktest`でインストール不要

---
## トレンド入り理由の推測

CloakBrowserが本日567スターを獲得してトレンド4位に入った背景には、AIエージェントとWebスクレイピングの需要急増がある。2026年現在、LLMベースの自動化エージェントがCloudflareやPerimeterXなどのボット検出に次々と阻まれる問題が深刻化しており、「ボット検出を突破するブラウザ」というソリューションへの関心が爆発的に高まっている。`ai-agents`トピックを持つことからも、AI開発者コミュニティを強く意識したポジショニングであることがわかる。

技術的な差別化ポイントも注目を集めた要因だ。多くの競合が「JSインジェクション」や「設定変更」に頼る中、本プロジェクトはChromiumのC++ソースコード自体を49箇所パッチするというアプローチを採用している。この「本物のブラウザに見える」という特性は、検出回避に関心を持つセキュリティ研究者や自動化エンジニアから強い支持を集めた。pushed_atが本日（2026-05-10）であることも、新バージョンリリースがトレンド入りを後押しした可能性が高い。

さらに、`pip install cloakbrowser`というシンプルなインストール体験と、Playwright既存ユーザーへの3行移行という低い導入障壁が口コミ拡散に寄与した。無料・オープンソース・サブスクリプション不要という点で、商用アンチ検出ブラウザ（Multiloginなど月額数万円）の代替として注目され、コスト削減を求める開発者・スクレイピング業者からの支持を集めた。

---
## 関連リンク

- https://github.com/CloakHQ/CloakBrowser
- https://cloakbrowser.dev/

---
## メモ
