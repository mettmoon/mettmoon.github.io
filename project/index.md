---
layout: default
title: Proejct
search_omit: true
---

<ul class="post-list">
{% for post in site.categories.project %} 
  <li><article><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}{% if post.excerpt %} <span class="excerpt">{{ post.excerpt }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>