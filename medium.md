---
layout: page
title: Artigos antigos publicados no Medium
permalink: /medium/
---
Aqui você encontrará todos os meus artigos sobre Análise de Dados e Analytics.

:)

<ul>
  {% for page in site.categories.medium %}
    <li>
      <a href="{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>