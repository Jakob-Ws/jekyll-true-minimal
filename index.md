---
layout: default
title: home
---
# Schön das du da bist! 

## Neuste Artikel
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>