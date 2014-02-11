---
layout: page
title: Silverlightを囲む会にようこそ！
tagline: Supporting tagline
---
{% include JB/setup %}

SilverlightSquareとは、Silverlight関連の勉強会を行うコミュニティ団体です  
2008/3/14～2012/7/7 までの間、Silverlightに関する勉強会を東京、大阪、名古屋にて開催していました

勉強会「Silverlightを囲む会」では、Silverlightの基礎知識や最新情報などを紹介し  
また、参加するだけに留まらない勉強会にするために、人とのつながりを重視したセッションを組み込んだりもしていました

このページでは、過去の開催履歴を記載しています  
代表 ： 遥 佐保 （はるか さお）

Google Groupのメーリングリストは[こちら](http://groups.google.com/group/silverlight_round_table)です。

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
