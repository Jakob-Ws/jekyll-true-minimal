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
## Lehrmaterial
Materialien, welche ich für meine Tutorien nutze.
- [http://homvw.de/gdm/](Grundlagen der Mathematik])
