---
layout: home
title: AI那些事
---

# AI那些事

> 每天三更，带你读懂AI世界的那些事儿

欢迎来到「AI那些事」！我是miki，每天早8点、中午11:30、晚上7点，为你解读最新的AI新闻。

## 关于本站

这是一个专注于AI领域新闻解读的博客，用轻松幽默的方式，带你了解人工智能世界的最新动态。

## 最新文章

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

---

*Powered by Jekyll & GitHub Pages*
