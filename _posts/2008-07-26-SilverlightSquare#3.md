---
layout: page
title : "Silverlightを囲む会in大阪#3"
category : "Osaka"
tagline: "Supporting tagline"
tags : [Osaka]
---
{% include JB/setup %}

今回はなんと、[Flex User Group](http://www.fxug.net/) さんとの共催が決定しました！

イベント名は "Fleverlight勉強会" です  
　( Silverlightを囲む会 in大阪#3 & [Flex3勉強会第46回@大阪](http://www.fxug.net/modules/bwiki/index.php?cmd=read&page=Flex3%CA%D9%B6%AF%B2%F1%C2%E846%B2%F3%A1%F7%C2%E7%BA%E5%BB%B2%B2%C3%BC%F5%C9%D5) )

## 日時
2008/7/26(土) 2:30p.m～5:30p.m (3時間)

## 会場
大阪産業創造館17F フリースペース  
〒541-0053 大阪市中央区本町1-4-5  
[http://www.sansokan.jp/map/](http://www.sansokan.jp/map/)  
最寄り駅は地下鉄堺筋本町です
  
## 参加費
￥200.-

★★★浴衣でのご来場、大歓迎★★★

浴衣など、日本の風物詩を感じさせる服装でいらっしゃった方には、プレゼント進呈します！  
→プレゼントは手作りうちわでした～

## セッション内容
2:15 p.m. ～ 受付

2:30～2:40   挨拶  
2:40～       セッション開始  

2:40～3:00 「Flex & Silverlightをはじめるには？」  (20分)
: [蜜葉](http://c-mitsuba.com/) ＆ALPS 資料  

3:00～3:20 「Silverlight2でRIA開発」   (20分)
: [遥佐保](http://blog.livedoor.jp/haruka_sao/) 資料 [デモ](http://silverlightsquare.com/source/03_Silverlight_RIA.lzh)  

3:20～3:30 「Flex Builderでサンプル作り」 (10分) 
: hirossy  資料  

3:30～3:40 「Fleverlight@大阪」  (10分)
: sato-shi 資料  

3:40～3:50 ☆☆☆ 10分休憩 ☆☆☆  
3:50～4:20 ライトニングトーク  

「Silverlight IDE」  
: coma2n

「いさみんの初心者講座　ライブラリ紹介編」
:いさみん 資料  

「WPFとSilverlight」  
: [青柳臣一](http://shinichiaoyagi.blogspot.jp/)

「Air Demo」  
: gori 資料  

#### 4:20～5:00   「FlexとSilverlightで作ってみよう！LiveCoding」 (40分)  
* (F)コーディング ： [nitoyon](http://tech.nitoyon.com/ja/) [解説ブログ](http://tech.nitoyon.com/ja/blog/2008/07/28/fleverlight1/)  
* (S)コーディング ： [k_maru](http://kmaru.hatenablog.com/)   [コード](http://silverlightsquare.com/source/03_LiveCoding.Silverlight.zip)  
* (F)コード解説   ： hirossy  
* (S)コード解説   ： 青柳臣一  

5:00～5:15    ちょっとした参加型イベント  (15分)

5:15～5:30    最後の挨拶、アンケート記入、後片付け  
5:30～           退出（ 希望者は懇親会へ、参加費は別途 およそ￥4,000.- 程度です）  


Silverlightサイドで17名、Flexサイドで25名、計42名のみなさまに参加いただきました。ありがとうございました。

## 参加レポート

今回参加してくださった ynagaoさんが、レポートを書いてくださりました！

ynagaoさん、ありがとうございました！！

7/26 sliverlight#3 Flex3#46  
*** session ***  
o 蜜葉さん (Silverlight) 　　ALPSさん (Flex)  
     「Flex&Silverlight をはじめるには？」  
- 開発ツールの紹介がメイン？  
- Web デザイナーさん向けの開発ツール？  

- Flex とは？  
プログラマー向けの Flash で、swf を簡易に生成できる。  
特徴は、コンポーネントが多く、OS に依存しない。  
デザインは MXML で開発言語は ActionScript で、CSS などもある。  
JavaScript や Java を触ったことのある人に、親和性が高い。  
Flex SDK (配布)、Flex Builder (Eclipse ベース) GUI ベースで開発可能。  

- Silverlight とは？  
RIA (Rich Interactive Application) を XAP ファイル (ZIP 形式) として生成する。  
Expression Blend で UI を生成。開発言語が多い。Linux だと Moonlight で。  
デザインは XAML で、言語は JavaScript (Silverlight1), C#, IronPython, IronRuby, VB.NET (Silverlight2) で、間口が広いが情報が少ない (;_;)  
デモ「Non Cording Silverlight (Popfly で。Virtual Earth めいたことを)」  

o sao さん  
   「Silverlight2 で RIA 開発 (Deep Zoom)」  

- Silverlight でできること  
CLR, DLR.  
「開発者の得意な言語で開発できる。」っていうけど、VS2008 では C# と VB.NET だけ。  

RSS 読み込みのサンプル (RSS/Atom Feed Reader)  
Java Script, HTML DOM などを呼び出せる。  
Data Grid (Sounds Familiar) > ビジネスアプリに活用できる  
DRM (Gyao は Silverlight1 で実装？)  

- Deep Zoom をつかってみよう  
Google Map や Live Search Maps のようなことを実現可能。  
デモとして Virtual Earth の Silverlight Deep Zoom 版。  

Deep Zoom Composer でデモ。  
* 起動して、適当な画像を選んで読み込み、配置して編集 (ページデザイン？) 。  
* 拡大、縮小もできるらしい。  

Mipmap 手法を使って、表示するように見せかけ (実際にはロードしない) て、シームレスに動くように見せる。画像を分割縮小して、読み込み時間を短縮。  

o hirossy さん  
    「Flex Builder でサンプル作り」  
- MXML で画面を作る。  
mx ネームスペースで、タグの階層構造で画面を作る。デザインモードで画面を確認。  
GUI で作成 (コンポーネントの貼り付け、編集など) がタグ構造に反映される。  
コンポーネントは用意されているが、自作もできる。  
スタイル、Skin 設定で見た目を変更できる。  
無論、手書き (コーディング) でも設定など可能。  

動的にプロパティを変更できる。Flash とは作り方が違う。  

o sato-shiさん  
 　「fleverlight＠大阪」  
- ユーザインターフェースデザイン  
AIR アプリケーションでデモ。内部は Flex で作成。  
デザインを全部外すと、内部実装はそのまま Flex の基本デザインで稼動。  
-> デザインと実装の分離が可能  

- アーキテクチャデザイン  
サーバ通信の設計を大事に。  
デモ。本をめくるアプリケーション。  

*** ライトニングトーク ***  
o coma2n さん  
     「Silverlight IDE - ブラウザから開発できる Web アプリケーション」  
画面デザインと C# での実装をそれぞれコーディング可能。  

ライトニングコーディングでデモ。  
サーバサイドに開発ツールを用意することで、「いつでもどこでも」Silverlight の開発が可能。  

o いさみんさん  
    「初心者講座 ライブラリ紹介編 (Flex(ActionScrpt3) ?)」  
サンプル : Tweener, 物理エンジン (引越し奉行 など), Audi のサイト  

o 青柳さん  
    「WPF (EXE) と Silverlight (マルチプラットフォーム) 」  
* 実は Silverilght を dis ってる？  

WPF は .NET Freamwork 3 と 3.5 でサポート  

XAML + マネージドコード で生成。  
コードの内容は、ほとんど Silverlight と同じ。  

WPF にはあるけど Silverlight にはない、という機能はたくさんある。エンジンもぜんぜんちがう。ウィンドウの生成は Silverlight ではできない。  

o gori さん  
    「Adobe Air」  
Air はデスクトップアプリで、Web アプリ技術を使え、ローカル資源にアクセス可能。  

デモ。自分専用のブラウザ。  

*** ライブコーディング ***  
o nitoyon さん (Flex)、k_maru さん (Sliverlight)  
    同じ機能を Silverlight と Flex で同時にコーディング (20 分)  

素材 : 0 から 9 までのイラストを描いた画像。  
お題 : 1 から 42 (参加者数) までの数字を乱数表示。(ランダム、アミダ、etc...)  

全体的に、Flex は見た目優先。Sliverlight は遅れを取り戻すために、ロジック優先の流れ。  
Flex 側が ThinkPad で、Silverlight 側が MacBook 使ってるのも面白い (^^;  
Flex 側は、開始 6 分で大枠完成！残り時間で創意工夫しまくり。結局、2 種類のアプリを生成。  
Silverlight 側は残り 2 分くらいでようやく機能実現。  

- Flex は秀丸 (コードアシスタントつき) でコーディング (ヘルプからサンプルコピー)。ActionScript と tweener を使う。コンパイルは rascut というツールを使用。  

ボタンクリックで 1 から 42 までの数をランダム表示するように仕込む。  
数字がカウンタ回転表示されるように。回転がだんだん遅く表示される。  
(random 関数使用？)  

- Silverlight は VS2008 で作成。  
ネットワークエラーになる。ソリューションの作り方がおかしい？  
* 画像ファイルが、Web ブラウザから見える位置にない。  
* 青柳さんからダメだしが。。。  

*** 参加型イベント ***   
Flex 作、Silverlight 作のツールでそれぞれビンゴして、参加者にプレゼント。  
2 つとも、初参加の方にプレゼントがあたりました。3名のみなさまに参加いただきました。　ありがとうございました。  

![Suppoted by VSUG](http://silverlightsquare.com/custom/120x90_supported_by_vsug.gif)
