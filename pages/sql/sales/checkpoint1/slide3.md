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
  title="取得結果をイメージしよう"
/>


<div class="main">
  <div class="talk">
    <Talk
      from="wanko"
      text="まずは取得結果をイメージするんですね。月ごとの売上を知りたいので、「請求開始年月」「売上」を取得できれば良いと思います！" />
    <Talk
      from="hitsuji"
      text="その通りじゃ。それらを取得するのに必要なテーブルはイメージつくかな？" />
    <Talk
      from="wanko"
      text="えーと、売上の取得なので、請求に関するテーブルでしょうか。" />
    <Talk
      from="hitsuji"
      text="良いぞ。テーブルの一覧を見てみるとbilling_periodsテーブルというものがあるから、次のスライドで一緒に確認してみよう。" />
  </div>
  <Image url="../1-3-1-fs8.png" />
</div>