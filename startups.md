---
layout: page
title: "Artigos sobre Startups"
permalink: /startup.html
hide: true
---
Aqui você encontrará todos os meus posts sobre startups.

:)

<ul>
  {% for post in site.categories.startup limit:50 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>