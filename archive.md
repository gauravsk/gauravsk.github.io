---
layout: page
title: Archive
---


{% for post in site.posts %}
{% unless post.categories contains "recipes" %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endunless %}
{% endfor %}
