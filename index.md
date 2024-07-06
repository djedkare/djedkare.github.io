---
layout: default
title: Index
---

# Index
{{ site.time }}

## Posts
{% for post in site.posts %}
* **[{{ post.title }}]({{ post.url }})** {{ page.date }}
{% endfor %}