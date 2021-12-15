---
layout: post
title:  "Hello World"
date:   2021-12-15 09:29:20 +0800
categories: 
---



在Markdown中可以通过如下语法插入图片。

```
![](/markdown-image/080103_hakkai_fuji.jpg)
```

<figure>
  <img src="/markdown-image/080103_hakkai_fuji.jpg">
  <figcaption>By 名古屋太郎 - 投稿者が撮影。PENTAX K10D + smc PENTAX-A 1:1.2 50mm + C.PL FILTER, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=6002925</figcaption>
</figure>

不过如果要调整图片的大小和对齐方式，Markdown的语法就不太支持，此时需要内嵌html标签来调整。

```
<figure>
<img src="/markdown-image/080103_hakkai_fuji.jpg" width="10%" height="10%">
</figure>
```

<img src="https://wanguanglu.github.io/markdown-image/080103_hakkai_fuji.jpg" width="10%" height="10%">
