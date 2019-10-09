---
key: parallel_simulated
title: Golangで並行シミュレーテッドアニーリング
id: parallel_simulated
format: conference
level: all
talkType: short_session
tags:
  - S-9A
speakers:
  - tsuji_daishiro
videoId: null
presentation: null
draft: false
---
メタヒューリスティクスの手法のひとつであるシミュレーテッドアニーリングは様々な最適化問題へ応用することができる汎用アルゴリズムです。 良質な解を得るためには十分な計算時間が必要であり、様々な並行化の研究があります。 私は温度並列シミュレーテッドアニーリング(TPSA)をGolangで実装しました。Golangの並行機構とマッチして、自然にTPSAを実装することができます。 また、巡回セールスマン問題にTPSAを適用したときに良質な結果が得られたことを示します。あわせてgonum/plotパッケージとWebsocketを組み合わせて、ブラウザ上でリアルタイムに解が収束する過程を確認します。
