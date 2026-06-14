# Geo Quiz 🌍

白地図に国名をドラッグ＆ドロップして覚える地理クイズ。
Drag country names onto a blank map to learn world geography.

日本語版・英語版の2言語。現在「ヨーロッパ（44か国）」と「中東と周辺国（30か国）」をプレイできます。

## 公開方法 / How to publish (GitHub Pages)

1. このフォルダの中身を **そのまま** リポジトリのルートに置きます（`index.html` がトップに来るようにします）。
2. GitHub のリポジトリで **Settings → Pages** を開きます。
3. **Build and deployment → Source** を「Deploy from a branch」にします。
4. **Branch** を `main`（または公開したいブランチ）、フォルダを `/ (root)` に設定して **Save**。
5. 数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます。

> 外部ライブラリ・通信は一切使っていない自己完結のサイトです。ファイルを置くだけで動きます。

## ファイル構成 / Structure

```
index.html              TOP（言語選択 / Language select）
updates.html            更新情報 / Updates
assets/style.css        共通スタイル / Shared styles
ja/index.html           日本語ハブ（地域選択）
ja/europe.html          ヨーロッパ（44か国）
ja/middle-east.html     中東と周辺国（30か国）
en/index.html           English hub (region select)
en/europe.html          Europe (44 countries)
en/middle-east.html     Middle East (30 countries)
```

## 遊び方 / How to play

- 下のリストから国名をドラッグし、地図上の正しい場所でドロップします。
- 正解すると国が緑色になり、国名ラベルが表示されます。間違えるとミス数が増えます。
- 全問正解でお祝い演出、ミスなしで全問正解すると「PERFECT!」のスペシャル演出が出ます。

## 隠しコマンド（演出確認用）/ Hidden commands

- キーボード: `Shift + W`（通常クリア） / `Shift + P`（パーフェクト）、または `win` / `perfect` とタイプ
- スマホ: 左上の 🌍 アイコンを素早く5回タップ

## 今後の予定 / Roadmap

アメリカ（州）・南米・東南アジア・アフリカ・オセアニアを順次追加予定。
（各ハブページに「準備中 / SOON」として表示しています）
