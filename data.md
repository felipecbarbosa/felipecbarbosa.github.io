---
layout: page
title: Artigos sobre Data
permalink: /data/
hide: true
---
Aqui você encontrará todos os meus artigos sobre Análise de Dados e Analytics.

:)

<ul>
  {% for post in site.categories.data %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>