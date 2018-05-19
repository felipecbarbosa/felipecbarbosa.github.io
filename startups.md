---
layout: page
title: Artigos sobre Startups
permalink: /startups/
hide: true
---
Aqui você encontrará todos os meus artigos sobre Startups.

:)

<ul>
  {% for post in site.categories.startup %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>