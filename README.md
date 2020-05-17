# redmine-headline

Webサイト headline.redmine.jp のソースコードです。

スタティックサイト生成ツール [Hugo](https://gohugo.io/) と [hugonews](https://themes.gohugo.io/hugonews/) テーマを使用しています。


## 新しい記事の追加

`hugo new` を以下のように実行してください。 `content/items/2020/05/redmine-tokyo-18.md` に記事のひな型が生成されます。記事は年月ごとにディレクトリに分類して格納します。

```
hugo new items/2020/05/redmine-tokyo-18.md
```

生成された記事のひな型を開き、 `title`、`itemurl`、`tags` を適宜書き換えてください。

```
---
title: "【オンライン開催】第18回redmine.tokyo勉強会 (2020年5月23日)"
date: 2020-05-17T11:06:41+09:00
itemurl: "https://redmine.tokyo/versions/35"
sites: ""
tags: ["event"]
draft: false
---

```

## ローカル環境でのサイトのプレビュー

コマンドラインで `hugo server` を実行してWebサーバを起動したあと、 http://localhost:1313/ にアクセスしてください。

```
hugo server
```

ブラウザでサイトをプレビュー中にエディタで記事を編集すると、ブラウザで表示中のページも自動的に更新されます。
