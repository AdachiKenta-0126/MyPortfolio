---
title: "パントマイムセンシング"
date: 2023-04-06T13:50:47+09:00
featured: true
description: "現在，大学院で行っている卒業研究<br>
スマートフォンに含まれるセンサーの情報からパントマイムの上手さを推定し<br>
適切なフィードバックを行うことを目的にしている．<br>
分野としてはセンシング処理と人間拡張である"
tags: ["Kotlin","Android","パントマイム","研究"]
image: "/img/AppViewpantomime.png"
link: "https://github.com/AdachiKenta-0126/pantomime"
fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 500
sitemap:
  priority : 0.8
---
このアプリでは事前研究で得られた上手さと加速度センサのノルムの平均の関係から得られた

回帰直線の式を用いてセンシングを行い，センシング結果からパントマイムの上手さの評価を行う

以下の図のように状況によって加速度センサのノルムの値に特徴が出ることが示唆された
![WebView](/img/pantomimeData.png)
