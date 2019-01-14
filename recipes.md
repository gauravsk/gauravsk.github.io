---
layout: page
title: Recipes
---

I am listing some recipes here for my own convenience. I plan to grow this collection over time.

<ol>
  {% for post in site.categories.recipes %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ol>
