---
layout: post
title:  "Markdown中调整图片的大小和位置"
date:   2021-12-15 09:29:20 +0800
categories: 
---



在Markdown中可以通过如下语法插入图片。

```markdown
![](https://lmg.jj20.com/up/allimg/512/011212125536/120112125536-2-1200.jpg)
```

![](https://lmg.jj20.com/up/allimg/512/011212125536/120112125536-2-1200.jpg)


不过如果要调整图片的大小和对齐方式，Markdown的语法就不太支持，此时需要内嵌html标签来调整。

```html
<figure>
<img src="https://lmg.jj20.com/up/allimg/512/011212125536/120112125536-2-1200.jpg" width="10%" height="10%">
</figure>
```

<figure>
  <img src="https://lmg.jj20.com/up/allimg/512/011212125536/120112125536-2-1200.jpg" width="10%" height="10%">
</figure>



调整对齐方式为左对齐

```html
<figure>
<img src="https://lmg.jj20.com/up/allimg/512/011212125536/120112125536-2-1200.jpg" width="10%" height="10%" align="left">
</figure>
```

<figure>
<img src="https://lmg.jj20.com/up/allimg/512/011212125536/120112125536-2-1200.jpg" width="10%" height="10%" align="left">
</figure>
