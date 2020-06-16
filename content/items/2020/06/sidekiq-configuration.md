---
title: "Sidekiq configuration"
date: 2020-06-16T07:28:23+09:00
itemurl: "https://www.redmine.org/projects/redmine/wiki/SidekiqConfiguration"
sites: ""
tags: ["installation"]
draft: false
card: false
---

Redmineの通知メールの配信をバックグラウンドで行うためのキューイングバックエンドとしてSideKiqを使うための手順。Redmine 4.0以降では通知メールの非同期送信に対応。実運用環境ではデフォルトのinlineアダプタではなくSidekiqなどの使用が推奨。
