---
title: CSS Nite LP39「Coder's High 2015：コーディングスタイルの理想と現実」に参加しました
description: CSS Nite LP39「Coder's High 2015：コーディングスタイルの理想と現実」に参加した話。
date: 2015-02-07
tags: web
---

2015年2月7日開催の、[CSS Nite LP39「Coder's High 2015：コーディングスタイルの理想と現実」](http://cssnite.jp/lp/lp39/)に参加しました。  
CSS Nite は After Dark には参加したことがあったのですが、LP は初参加。

理想は理想だけど現実は色々あるから対処しなきゃいけないよねっていうことの対処方法のところに興味があったので、そこの話を楽しみにしていました。


## 興味深かった話

### 「ビルドツールはじめの一歩」

ピクセルグリッドの宇野さん、坂巻さん、小山田さんのセッション。

セッションの中で shift_jis のファイルをタスクランナーでどう処理するか？というのがあり、やはりどこでも同じ苦労をしているのだなと。  
自分も今の案件が大規模かつ shift_jis 案件でタスクランナーの設定にかなり時間を使ったので、このあたりの情報はもっと共有されてもいいのかなと思いました。

**サンプルファイル**  
[https://github.com/geckotang/cssnite-lp39](https://github.com/geckotang/cssnite-lp39)  
[https://github.com/yomotsu/cssnite_lp39](https://github.com/yomotsu/cssnite_lp39)


### music.jpのリファクタリング before / after

まぼろしの小林さんとエムティーアイの宮地さんのセッション。

「モジュールにないものはすべて断る」  
でデザイナーとの中が最悪に。そりゃそうですよね。でも気持ちはわかります。


### 柔軟なコンポーネント設計のためのCSS

こちらもピクセルグリッドの高津戸さんのセッション。

仕事をするうえで想像力を働かせることが一番重要なのではないかと最近思っていて、それはデザインもコーディングもシステム開発もすべて共通することなんじゃないかと。  
幅が狭いとき、特定のエレメントがなくなったとき、文字量が増減したとき、などなど想像力を働かせて実装をしないと出し戻しが増えて工数とストレスが増加してしまうので、各自がなるべく柔軟に実装をしておくことがやっぱ重要だよねって再確認しました。
