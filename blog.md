---
title: Alethiometry
layout: alethiometry
---

<ul id="blog">
  {% for blog in site.blogs %}
    <li>
      <h2><a href="{{ blog.url }}">{{ blog.title }}</a></h2>
      {{ blog.excerpt }}
    </li>
  {% endfor %}
</ul>
