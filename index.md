---
layout: default
title: Index
---

{% link index.md %}

## Posts
{% for post in site.posts %}
* **[{{ post.title }}]({{ post.url }})** {{ post.date | date: "%Y, %b %d" }}
{% endfor %}

## Pages
{% for page in site.pages %}
* **[{{ page.title }}]({{ page.url }})**
{% endfor %}

***


last rebuilt: {{ site.time }}