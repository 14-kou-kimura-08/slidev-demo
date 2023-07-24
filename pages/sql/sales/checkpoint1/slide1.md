---
# try also 'default' to start simple
theme: seriph
# page transition
transition: slide-left
# use UnoCSS
css: index.css
layout: image
image: /background.png
---

<Header
  title="売上減少に関する原因を調べよう"
  description="利用するテーブルやカラムを把握しましょう。「請求開始日」はstart_date、「売上」は請求金額を年月ごとにSUMで集計します。また「支払い状況」が`paid`（支払完了）の請求が売上に該当します。"
/>

<div class="main">
  <div class="talk">
    <Talk
      from="wanko"
      text="仙人、サービスの売上がどうなっているのかデータを見たいのですが、どのようにやれば良いでしょうか？" />
    <Talk
      from="hitsuji"
      text="うむ、一緒にデータを分析していこう。サービスの概要については右の図を参考にするのが良いぞ。" />
    <Talk
      from="wanko"
      text="仙人、サービスの売上がどうなっているのかデータを見たいのですが、どのようにやれば良いでしょうか？" />
  </div>
  <Image url="../1-1-1-fs8.png" />
</div>