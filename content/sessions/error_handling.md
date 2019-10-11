---
key: error_handling
title: Go1.13以後のエラーハンドリングについて語ろう
id: error_handling
format: conference
talkType: lt_session
level: beginner
inner: true
tags:
  - LT2
speakers:
  - ciarana
videoId: null
presentation: null
draft: false
---
これまでの error は、それがどこで発生したのか関数呼び出しを辿らなければ容易に判別できませんでした。Go1.13からは、標準パッケージ errors にスタックトレースを追うための機能が加わり、多くの Gopher がこの機能を使い始めます。本セッションでは、新しく追加された機能の紹介をし、その機能を使う上での注意点をお話しします。

