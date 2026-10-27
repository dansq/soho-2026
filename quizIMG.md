---
layout: quiz
title: 画像クイズ
primary_color: "#059669"
shuffle_questions: false
shuffle_answers: true
siteNav: true
---

# AI画像クイズ
{% capture quiz_questions %}

### サッカー
AIで作った画像はどっち？

1. [x] ![wat]({% link assets/images/soccerA.jpeg %})  
><br>・腕と手が歪んでいる  
>・草が舞っているが、地面には穴が開いていない  
>・顔は奇妙だ  
1. [ ] ![wat]({% link assets/images/soccerB.jpg %})  
><br>本物

### ウンピョウ

1. [x] ![wat]({% link assets/images/leopardA.jpeg %})  
><br>・テーブルには脚がない  
>・バケツとヒョウ柄のプロポーションがおかしく見える  
1. [ ] ![wat]({% link assets/images/leopardB.jpg %})  
><br>本物


### モトクロス

1. [x] ![wat]({% link assets/images/motocrossA.jpeg %})  
><br>・左側のバナーには「HONDDA」と書かれている。  
>・下のステッカーとヘルメットのステッカの文字が歪んでいる  
>・砂利はぼやけているが、車輪は時が止まったかのように見える  
1. [ ] ![wat]({% link assets/images/motocrossB.jpg %})  
><br>本物


### ライオン

1. [x] ![wat]({% link assets/images/lionsA.jpeg %})  
><br>光源の位置と影の落ち方が一致しない   
1. [ ] ![wat]({% link assets/images/lionsB.jpg %})  
><br>本物


### 卓球

1. [x] ![wat]({% link assets/images/pingpongA.jpeg %})  
><br>・選手はネットの中央に位置している     
><br>・群衆にいくつかの問題がある    
1. [ ] ![wat]({% link assets/images/pingpongB.jpg %})  
><br>本物


### 新幹線

1. [x] ![wat]({% link assets/images/shinkansenA.jpeg %})  
><br>・1960年代の写真にしては解像度が高すぎる    
><br>・天井に映る像は写真の全てと一致しない  
1. [ ] ![wat]({% link assets/images/shinkansenB.jpg %})  
><br>本物

### 鉄道操車場

1. [x] ![wat]({% link assets/images/trainyardA.jpeg %})  
><br>・右側では、線路が突然途切れている   
1. [ ] ![wat]({% link assets/images/trainyardB.jpg %})  
><br>本物


### 汽車

1. [x] ![wat]({% link assets/images/trainA.jpeg %})  
><br>・実際の描画・塗装ツールと一致しない、画像のぼやけたディテール  
1. [ ] ![wat]({% link assets/images/trainB.jpg %})  
><br>本物

{% endcapture %}

{% include quizdown.html questions=quiz_questions %}