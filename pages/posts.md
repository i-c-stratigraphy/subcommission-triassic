---
layout: page
title: Posts
permalink: /posts
---

## Posts

Research articles, reports, announcements, and news from Albertiana and the Subcommission on Triassic Stratigraphy.

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.date | date: "%e %B %Y" }}{% if post.categories.size > 0 %} · {{ post.categories | join: ', ' }}{% endif %}

<hr />

{% endfor %}
