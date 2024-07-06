---
layout: default
title: Index
---

# Index
{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }}) {{ post.excerpt }}
{% endfor %}