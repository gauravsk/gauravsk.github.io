---
layout: page
title: 
---

I will keep track of my non-academic reading here (starting 9 March 2019). I hope that logging my activity makes me a more active reader. 

<ol>
{% for post in site.categories.bookreport %}
{% if post.url %}
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}
</ol>
  