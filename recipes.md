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


#### Basics/essentials
<ol>
  {% for post in site.categories.recipes-basics%}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ol>

#### Vegetable sides
<ol>
  {% for post in site.categories.recipes-bhaji%}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ol>


#### Rice
<ol>
  {% for post in site.categories.recipes-rice%}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ol>



#### Other main courses 
<ol>
  {% for post in site.categories.recipes-otherMeals%}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ol>

#### Dessert
<ol>
  {% for post in site.categories.recipes-dessert%}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ol>
