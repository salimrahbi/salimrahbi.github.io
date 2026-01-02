---
layout: default
title: "الرئيسية"
---

## المقالات

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
