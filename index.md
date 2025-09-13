---
layout: default
title: XUSB
---

# Welcome to XUSB.NET
Hello test

## 最新文章
<ul>
{% for post in site.posts limit:5 %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span style="color:#777">({{ post.date | date: "%Y-%m-%d" }})</span>
  </li>
{% endfor %}
</ul>

{% seo %}
