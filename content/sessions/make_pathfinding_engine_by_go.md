---
key: make_pathfinding_engine_by_go
title: Go で"超高速"な経路探索エンジンをつくる
id: make_pathfinding_engine_by_go
format: conference
talkType: long_session
level: beginner
tags:
  - L-11H
speakers:
  - avvmoto_stmasnotes
videoId: null
presentation: null
draft: false
---
カーナビはどうしてあれほど運転ルートを高速に計算できるか、気になったことはありませんか？  
本トークでは、 実際にGoで""超高速""な経路探索エンジンを作成したときに用いた、アルゴリズムと実装時の工夫・チューニングを紹介します。まず経路探索アルゴリズムはどういったものか、前提知識不要で説明します(ダイクストラ、Contraction Hierarchies )。次に Go で実装する上で必要になる、高速に巨大なサイズの slice や map を扱う工夫を紹介します。経路探索を題材に、Go の slice や map の仕組み、そして高速に扱う工夫を持ち帰っていただければ幸いです。
