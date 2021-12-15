---
layout: post
title:  "Markdown中调整图片的大小和位置"
date:   2021-12-15 09:29:20 +0800
categories: 
---



在Markdown中可以通过如下语法插入图片。

```markdown
![](/assets/img/markdown-image/snow.jpeg)
```

![](/assets/img/markdown-image/snow.jpeg)


不过如果要调整图片的大小和对齐方式，Markdown的语法就不太支持，此时需要内嵌html标签来调整。

```html
<figure>
<img src="/assets/img/markdown-image/snow.jpeg" width="10%" height="10%">
</figure>
```

<figure>
  <img src="/assets/img/markdown-image/snow.jpeg" width="10%" height="10%">
</figure>



调整对齐方式为左对齐

```html
<figure>
<img src="/assets/img/markdown-image/snow.jpeg" width="10%" height="10%" align="left">
</figure>
```

<figure>
<img src="/assets/img/markdown-image/snow.jpeg" width="10%" height="10%" align="left">
</figure>

