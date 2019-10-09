---
key: oss_performance_tuning_tips
title: OSS Performance Tuning Tips
id: oss_performance_tuning_tips
format: conference
talkType: long_session
level: intermediate
tags:
  - L-6H
speakers:
  - nao_yonashiro
draft: false
---
GoのOSSにPerformanceのPatchを投げるときの取り組み方を実際の事例ベースで紹介します. Breaking Changeをせずにパフォーマンス問題を解決するために何をやっているか (sync.Poolを使う, structにPoolを持つような拡張を施す(image/png.Encoder go1.9~), bufをメンバとして持ってReset可能な作りにする, 明示的にbufを渡す関数(io.Copy, io.CopyBuffer)も提供する, チューニングの制約にならないためにpublicな関数は減らす), go-gitやgo本体へ投げたPatchの紹介もします.
