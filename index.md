---
layout: default
title: Index
---

# Index
{{ site.time }}

## Posts
{% for post in site.posts %}
* **[{{ post.title }}]({{ post.url }})** {{ post.date | date: "%Y, %b %d" }}
{% endfor %}

## Pages
{% for page in site.pages %}
* **[{{ page.title }}]({{ page.url }})**
{% endfor %}

# h1

## h2

### h3

#### h4

##### h5