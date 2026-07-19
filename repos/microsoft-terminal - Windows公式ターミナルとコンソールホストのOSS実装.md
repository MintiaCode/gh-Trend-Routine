---
url: https://github.com/microsoft/terminal
saved: 2026-07-19
tags:
  - c++
  - trending
  - windows
  - console
  - terminal
  - command-line
  - wsl
  - cmd
  - hacktoberfest
  - contributions-welcome
  - windows-console
  - good-first-issue
  - windows-terminal
category: GitHub Trending
status: 未読
rating:
---

# microsoft/terminal

▎ Windows公式ターミナルとコンソールホストのOSS実装

ライセンス: MIT
言語: C++
スター数: ⭐ 104000 (+103 今日)
トレンド順位: #9 (2026-07-19)

---
## 概要

本リポジトリは、Microsoftが開発する新しいWindows Terminalと、従来のWindowsコンソールホスト(conhost.exe)のソースコードを同一プロジェクトとして公開したものです。タブ機能、リッチテキスト表示、テーマ設定、豊富なカスタマイズ性を備えたモダンなコマンドライン端末を提供しつつ、DirectWriteベースの描画エンジンやVTパーサーなど、旧来のWindows Consoleから刷新されたコンポーネントを再利用する設計になっています。Windows Terminal本体に加え、Windows Terminal Preview、ColorTool、Windows Console APIのサンプルプロジェクトなども含まれています。Microsoft StoreやGitHub Releases、winget、Chocolatey、Scoopなど複数の経路でインストールでき、Windows 10 build 19041以降で動作します。WSLやコマンドプロンプト、PowerShellを日常的に使う開発者・パワーユーザーを主な対象とした、Windowsのコマンドライン体験を支える基盤プロジェクトです。

---
## 主な機能・特徴

- タブ・ペイン管理 — 複数のシェルセッションを1つのウィンドウで管理
- リッチテキスト・テーマ機能 — 配色やフォントなど高いカスタマイズ性
- DirectWriteベース描画エンジン — GPUアクセラレーションによる高速レンダリング
- VTパーサー — 従来のWindows Consoleコンポーネントを刷新して再利用
- 複数インストール経路 — Microsoft Store、GitHub Releases、winget、Chocolatey、Scoopに対応
- conhost.exe同梱 — 従来型コンソールホストも同一リポジトリで管理
- ColorToolとサンプル同梱 — Windows Console APIの学習・カスタマイズ用ツールを提供

---
## トレンド入り理由の推測

Windows Terminalはすでに10万スターを超える定番プロジェクトであり、1日103スターという伸びはバズというより安定した継続的関心の表れと見られます。直近ではv1.24.11911.0(2026年7月16日)がリリースされたばかりで、今回のトレンド入りはこの新バージョン公開に伴うアップデート告知や機能追加がコミュニティで話題になったことが直接のきっかけと考えられます。

また、開発ツールとしてのターミナルはAIコーディングエージェントやCLIベースのワークフローが増える中で改めて注目度が高まっている領域です。Visual Studio 2026対応やWinUI開発ワークロードへの言及など、開発環境の継続的なモダナイズも背景にあり、Windows環境での開発者体験向上に関心を持つユーザー層から安定した支持を集め続けていることがトレンド入りの一因と推測されます。

---
## 関連リンク

- https://github.com/microsoft/terminal
- https://aka.ms/terminal

---
## メモ
