---
title: Blog
layout: blog
---

<ul id="blog">
  {% for blog in site.blogs %}
    <li>
      <h2><a href="{{ blog.url }}">{{ blog.title }}</a></h2>
      {{ blog.excerpt }}
    </li>
  {% endfor %}
</ul>
