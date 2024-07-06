---
layout: default
title: Index
---

# Index
{% for post in site.posts %}
* **[{{ post.title }}]({{ post.url }})** {{ page.date }}
{% endfor %}