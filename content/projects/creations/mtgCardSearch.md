---
title: "音声認識でMTGのカードを検索する"
date: 2023-04-26T16:45:13+09:00
featured: true
description: "MTG(Magic:The Gathering)のカードを音声認識によって検索を行い表示します<br>マイクを使って検索ができます"
tags: ["Python","アプリ","音声認識","MTG"]
image: "/img/search.png"
link: "https://github.com/AdachiKenta-0126/mtg_card_search"
fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 500
sitemap:
  priority : 0.8
---

MTG(Magic:The Gathering)のカードを音声認識によって検索を行い表示します

mtgsdk(https://github.com/MagicTheGathering/mtg-sdk-python)を用いて

入力されたカード名で検索を行う

入力はマイクを使って入力できる

音声認識にはspeech_recognition(https://github.com/Uberi/speech_recognition)を用いた

![WebView](/img/search.png)
