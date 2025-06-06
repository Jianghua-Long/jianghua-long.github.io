---
layout: page
title: 项目展示
permalink: /projects/
---

这里是我的项目汇总。点击项目标题可查看详细介绍与进展。

{% for post in site.categories.项目 %}
- [{{ post.title }}]({{ post.url }})  
  <small>{{ post.date | date: "%Y-%m-%d" }}</small>  
  {{ post.excerpt | strip_html | truncate: 60 }}
{% endfor %}

---

如需了解更多，请浏览[博客首页](./)或[关于我](./about)。
