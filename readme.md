# NDLIIIFMobileReader

[![Netlify Status](https://api.netlify.com/api/v1/badges/fa89e537-e867-4888-9258-044adbf5d097/deploy-status)](https://app.netlify.com/sites/ndl-mobile-reader/deploys)

## 概要

モバイルデバイス向け UI フレームワーク[Ionic](https://ionicframework.com/)を使って構築した、国立国会図書館デジタルコレクションのIIIF APIと次世代デジタルライブラリーAPIを用いたモバイルリーダーです。資料検索やページ分割には[次世代デジタルライブラリー API](https://lab.ndl.go.jp/service/tsugidigi/apiinfo)を使用しています。

## デモページ

[こちら](https://ndl-mobile-reader.netlify.app/)からデモを利用できます。

## モバイルアプリ化

本リーダーを組み込んだiOS/Android対応のモバイルリーダー「じせデジリーダー」を開発中です（2024年度中に公開予定）．じせデジリーダーに収録予定の資料リストコンテンツを下記URLでオープンデータとして公開しています（CC BY 4.0）．

https://docs.google.com/spreadsheets/d/e/2PACX-1vRwCZ6AwKlzyhCAgI1vonFp8b9MktkZ_R5R2Xn6NET4gVjg_5MJhnrZuAnklBNLFSb-yzTqYl2ZMrfz/pubhtml


## 開発

node v.18 以上が必要です。

### 開発用サーバーの起動

`yarn start`

### ビルド

`yarn build`

## ライセンス

MIT License

## 開発者

橋本雄太（国立歴史民俗博物館）
Twitter: [yuta1984](https://twitter.com/yuta1984)
