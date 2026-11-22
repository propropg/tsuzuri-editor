<p align="center"><img src="https://raw.githubusercontent.com/propropg/tsuzuri-editor/main/icon.png" width="128" alt=""></p>

<h1 align="center">Tsuzuri Editor</h1>

<p align="center">Markdown をプレビューで読み、テキストを軽く編集するエディタ（無料・Windows / Mac）</p>

---

このリポジトリは **Tsuzuri Editor の配布用**です。ソースコードは置いていません。
最新版は [Releases](https://github.com/propropg/tsuzuri-editor/releases/latest) からダウンロードできます。紹介ページ：https://tsuzuri-editor.propropg.workers.dev/

## 入手

| OS | 入手方法 |
|---|---|
| Windows 10（1809 以降）/ 11 | [Releases](https://github.com/propropg/tsuzuri-editor/releases/latest) のインストーラ（`TsuzuriEditor-Setup-<版>.exe`）・ポータブル版（`TsuzuriEditor-Portable-<版>-x64.zip`） |
| macOS 12 以降 | [Releases](https://github.com/propropg/tsuzuri-editor/releases/latest) の dmg（Apple Silicon 用 `-arm64.dmg` / Intel 用 `-x64.dmg`） |

インストーラ・ポータブル版・dmg はコード署名をしていないため、初回の起動時に Windows SmartScreen や macOS Gatekeeper の確認が出ます。許可の手順は、配布ファイルに入っている「はじめにお読みください」をご覧ください。

## できること

- **Markdown**：開くと最初からプレビューで表示。エディタと左右に並べてスクロールを合わせる。表・数式（KaTeX）・図（Mermaid）・注意書き・注釈。アウトライン、20 種類のデザイン、PDF に出力
- **テキストエディタ**：行番号・桁ルーラー・空白や改行の記号・検索と置換（正規表現）・複数カーソル・矩形選択・折り返し。大文字⇔小文字・全角⇔半角・行の並べ替えなどの変換
- **色付け**：100 以上の言語。拡張子ごとに言語・タブ・折り返し・配色を決められる（タイプ別設定）
- **文字コード**：UTF-8・Shift_JIS・EUC-JP・UTF-16 を判定して開き、同じ文字コードで保存
- **比較**：左右に並べる・WinDiff 形式。違う文字にも印。タブ・保存したファイル・クリップボードと比べられる
- **フォルダ内を検索（Grep）**、タブと複数のウィンドウ、VS Code と同じショートカット、大きなファイルの軽量表示
- 画面は日本語・英語。ファイルの内容を外部に送信しません

## 使用許諾条件・免責事項

- **無料**で使えます（個人・会社とも。業務での使用を含みます）
- 改変・他のソフトウェアへの組み込み、販売・有償での配布、改変したものの配布、リバースエンジニアリングは禁止です。配布されたファイルを改変せず、無償で他の人に渡すことはできます
- オープンソースではありません。詳しくは、配布ファイルに同梱の「使用許諾条件（LICENSE）」をご覧ください
- **Tsuzuri Editor はファイルの内容を直接書き換えるツールです。使用によって生じたデータの消失・破損などについて、作者は責任を負いません。** 大切なファイルを編集する前に、必ずバックアップを取ってください

---

## English

This repository hosts the **downloads of Tsuzuri Editor** (no source code), a free, lightweight Markdown viewer and text editor. The user interface is available in Japanese and English.

- **Windows 10 (1809+) / 11**: the installer or portable zip on [Releases](https://github.com/propropg/tsuzuri-editor/releases/latest)
- **macOS 12+**: dmg on [Releases](https://github.com/propropg/tsuzuri-editor/releases/latest) (`-arm64` for Apple Silicon, `-x64` for Intel)

Features: Markdown preview (tables, math, Mermaid diagrams, PDF export), a text editor with a column ruler and syntax highlighting for 100+ languages, Shift_JIS / EUC-JP / UTF-16 support, a WinDiff-style file compare, find in folder (Grep), tabs and multiple windows, and VS Code keyboard shortcuts.

Free for personal and commercial use. Modification, resale, paid redistribution and reverse engineering are not permitted. This is not open source software. Always back up important files before editing them.

© 2026 propropg
