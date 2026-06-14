# Geo Quiz 🌍

白地図に国名（州名）をドラッグ＆ドロップして覚える地理クイズ。
Drag country/state names onto a blank map to learn world geography.

日本語版・英語版の2言語。全8地域がプレイできます。

| 地域 / Region | 数 | ja | en |
|---|---|---|---|
| ヨーロッパ / Europe | 44か国 | ja/europe.html | en/europe.html |
| 中東と周辺国 / Middle East | 30か国 | ja/middle-east.html | en/middle-east.html |
| アメリカ（州）/ USA | 50州 | ja/usa.html | en/usa.html |
| 南米 / South America | 13か国 | ja/south-america.html | en/south-america.html |
| 東南アジア / Southeast Asia | 11か国 | ja/southeast-asia.html | en/southeast-asia.html |
| 東アジア / East Asia | 6か国 | ja/east-asia.html | en/east-asia.html |
| アフリカ / Africa | 50か国 | ja/africa.html | en/africa.html |
| オセアニア / Oceania | 7か国 | ja/oceania.html | en/oceania.html |

## 公開方法 / How to publish (GitHub Pages)

1. このフォルダの中身を **そのまま** リポジトリのルートに置きます（`index.html` がトップに来るように）。
2. リポジトリの **Settings → Pages** を開きます。
3. **Source** を「Deploy from a branch」、**Branch** を `main` / フォルダを `/ (root)` にして **Save**。
4. 数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます。

外部ライブラリ・通信は使っていない自己完結のサイトです。

## ファイル構成 / Structure

```
index.html              TOP（言語選択）
updates.html            更新情報
assets/style.css        共通スタイル
ja/  ... 日本語版（index.html = 地域選択 ＋ 各地域ページ）
en/  ... English（index.html = region select ＋ region pages）
```

## 遊び方 / How to play

- 下のリストから名前をドラッグして地図の正しい場所にドロップ。
- 地図は拡大・縮小できます（＋／−ボタン、マウスホイール、スマホはピンチ）。ドラッグで移動も可能。
- ドラッグ中は指の少し上に十字の照準が出ます。小さな国もその照準を合わせてドロップできます。
- 全問正解でお祝い演出、ミスなしで全問正解すると「○○マスター」のスペシャル演出が出ます。

## 備考 / Notes

- アフリカは島しょ国（カーボベルデ等）を除く50か国を収録しています。
- 一部地域では地図の端に映る周辺国（ロシア・インド等）は出題対象外です。
