---
layout: quiz
title: 画像クイズ（A）
primary_color: "#059669"
shuffle_questions: false
shuffle_answers: true
siteNav: true
---

# AI画像クイズ（A）
{% capture quiz_questions %}

### サッカー
AIで作った画像はどっち？

1. [x] ![wat]({{ site.baseurl }}/assets/images/soccerA.jpeg)  
><br><span style="color:red">×</span>腕と手が歪んでいる。  
><br><span style="color:red">×</span>草が舞っているが、地面には穴が開いていない。  
><br><span style="color:red">×</span>顔は奇妙だ。  
1. [ ] ![wat]({{ site.baseurl }}/assets/images/soccerB.jpg)  
><br>本物

### ウンピョウ

1. [x] ![wat]({{ site.baseurl }}/assets/images/leopardA.jpeg)
><br><span style="color:red">×</span>テーブルには脚がない。  
><br><span style="color:red">×</span>バケツとヒョウ柄のプロポーションがおかしく見える。  
1. [ ] ![wat]({{ site.baseurl }}/assets/images/leopardB.jpg)
><br>本物


### モトクロス

1. [x] ![wat]({{ site.baseurl}}/assets/images/motocrossA.jpeg)
><br><span style="color:red">×</span>左側のバナーには「HONDDA」と書かれている。  
><br><span style="color:red">×</span>下のステッカーとヘルメットのステッカの文字が歪んでいる。  
><br><span style="color:red">×</span>砂利はぼやけているが、車輪は時が止まったかのように見える。  
1. [ ] ![wat]({{ site.baseurl }}/assets/images/motocrossB.jpg)
><br>本物


### ライオン

1. [x] ![wat]({{ site.baseurl }}/assets/images/lionsA.jpeg)
><br><span style="color:red">×</span>光源の位置と影の落ち方が一致しない。   
1. [ ] ![wat]({{ site.baseurl }}/assets/images/lionsB.jpg)
><br>本物


### 卓球

1. [x] ![wat]({{ site.baseurl }}/assets/images/pingpongA.jpeg)
><br><span style="color:red">×</span>選手はネットの中央に位置している。     
><br><span style="color:red">×</span>群衆にいくつかの問題がある。    
1. [ ] ![wat]({{ site.baseurl }}/assets/images/pingpongB.jpg)
><br>本物


### 新幹線

1. [x] ![wat]({{ site.baseurl }}/assets/images/shinkansenA.jpeg)
><br><span style="color:red">×</span>1960年代の写真にしては解像度が高すぎる。    
><br><span style="color:red">×</span>天井に映る像は写真の全てと一致しない。  
1. [ ] ![wat]({{ site.baseurl }}/assets/images/shinkansenB.jpg)
><br>本物

### 鉄道操車場

1. [x] ![wat]({{ site.baseurl }}/assets/images/trainyardA.jpeg)
><br><span style="color:red">×</span>右側では、線路が突然途切れている。   
1. [ ] ![wat]({{ site.baseurl }}/assets/images/trainyardB.jpg)
><br>本物


### 汽車

1. [x] ![wat]({{ site.baseurl }}/assets/images/trainA.jpeg)
><br><span style="color:red">×</span>実際の描画<br><span style="color:red">×</span>塗装ツールと一致しない、画像のぼやけたディテール。  
1. [ ] ![wat]({{ site.baseurl }}/assets/images/trainB.jpg)
><br>本物

{% endcapture %}

{% include quizdown.html questions=quiz_questions %}