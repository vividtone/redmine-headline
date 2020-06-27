---
title: "ユーザー一括登録用のシェル作りました"
date: 2020-06-27T11:49:56+09:00
itemurl: "https://qiita.com/sakuhi/items/5be9af95a9b2064df100"
sites: ""
tags: ["utility"]
draft: false
---

CSVファイルを読み込んでユーザーの一括登録を行うシェルスクリプト。bashとjqがあれば動作する。登録時にユーザーにメール通知を送れるのがほかの同種のツールに対する特長。

なおユーザーのインポート機能はRedmine 4.2 / RedMica 1.1以降では標準機能（[#33102](https://www.redmine.org/issues/33102)）だが、ユーザーへの通知は行われない。
