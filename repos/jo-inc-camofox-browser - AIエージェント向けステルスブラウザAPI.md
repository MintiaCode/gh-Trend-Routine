---
url: https://github.com/jo-inc/camofox-browser
saved: 2026-06-02
tags:
  - javascript
  - trending
  - ai-agent
  - anti-bot
  - antidetect-browser
  - automation
  - bot-detection
  - browser-automation
  - cloudflare-bypass
  - headless-browser
  - nodejs
  - playwright
  - puppeteer
  - scraping
  - stealth-browser
  - web-scraping
category: GitHub Trending
status: 未読
rating:
---

# jo-inc/camofox-browser

▎ AIエージェント向けステルスブラウザAPI

ライセンス: MIT
言語: JavaScript
スター数: ⭐ 6,229 (+103 今日)
トレンド順位: #19 (2026-06-02)

---
## 概要

camofox-browserは、AIエージェントがCloudflare・ボット検出・アンチスクレイピングを回避して実際のウェブを閲覧するためのステルスヘッドレスブラウザサーバーです。FirefoxフォークのCamoufoxをベースに、C++実装レベルでフィンガープリントを偽装（hardwareConcurrency・WebGL・AudioContext・スクリーン情報等）するため、JavaScriptシムよりも遥かに検出が困難です。Puppeteer/Playwrightのドロップイン代替としてREST APIを提供し、アクセシビリティスナップショットで生HTMLより約90%軽量な出力を実現します。安定した要素参照ID（e1, e2...）でクリック操作も確実で、ラズパイや5ドルVPSでも動作する軽量設計（アイドル時約40MB）が特徴です。

---
## 主な機能・特徴

- C++レベルフィンガープリント偽装 — WebGL・AudioContext・画面情報を根本から偽装
- Cloudflare・ボット検知回避 — 最も一般的な検知システムに対応
- アクセシビリティスナップショット — 生HTMLの約90%削減、トークン効率化
- 安定要素参照ID — `e1`, `e2`形式でクリック等の操作を確実に実行
- セッション分離 — ユーザーごとに独立したCookie/ストレージ
- プロキシ + GeoIP — 居住用プロキシ経由でロケール・タイムゾーン自動設定
- YouTube字幕取得 — yt-dlpでAPIキー不要の字幕抽出

---
## トレンド入り理由の推測

AIエージェントによるWebブラウジング需要が爆発的に増加する中、Cloudflareによるボット検出が強化されてPlaywrightやPuppeteerがブロックされるケースが増えています。camofox-browserはC++レベルのフィンガープリント偽装という技術的優位性を持つCamoufoxをエージェント向けAPIとして提供する点が評価されており、+103スターという今日の数字はAIエージェントエコシステム構築者から積極的に採用されていることを示しています。

pushed_atが2026-05-24と直近のメンテナンス履歴があり、実際の開発現場で使えるツールとしての信頼性が評価されています。jo-inc社が開発し個人AI「jo」のバックエンドで実際に使用していることも実績の裏付けとなり、「自社製品で実際に使っているツール」というストーリーがコミュニティへの説得力になっています。

---
## 関連リンク

- https://github.com/jo-inc/camofox-browser

---
## メモ
