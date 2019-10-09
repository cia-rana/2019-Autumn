---
key: analysis_docker_image
title: GoでDockerイメージを解析してCIを改善する方法
id: analysis_docker_image
format: conference
talkType: short_session
tags:
# - _languages
level: all
tags:
  - S-6H
speakers:
  - tomoya_amachi
videoId: null
presentation: null
draft: false
---
最近、AquaSecurityに買収され話題になったTrivyや、拙作のDockleはDockerイメージを静的解析して、状態をチェックするツールです。  
このツールを支えるfanalというライブラリを使うと、自分が利用しているDockerイメージを簡単に解析できます。そして、あなたのCI上で独自のチェックルールを作成することができるようになります。  
発表では実際に、ファイルの存在チェックやnginx.confの書式チェックを行うためのプロジェクトを作成します。
