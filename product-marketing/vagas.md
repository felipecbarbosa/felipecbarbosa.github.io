---
layout: page
title: "Vagas de Marketing de Produto em empresas Brasileiras"
hide: true
---

> [Quero ir direto para as vagas](#vagas-product-marketing)

Eu sou apaixonado pela área de [Marketing de Produtos](/marketing-de-produto/){:target="_blank"} desde que entrei no mundo de empresas de tecnologia lá em 2013. 

Foi num ambiente onde eu era a única pessoa de [negócios](/business/){:target="_blank"} em um time de desenvolvimento que precisar vestir o chapéu de [Marketing](/marketing/){:target="_blank"} mas também o de [Produto](/produto/){:target="_blank"}, Vendas, Suporte, Atendimento e Sucesso do Cliente.

Nessa época que comecei a juntar todas as pontas e ver que a disciplina de **Product Marketing** era a que fazia mais sentido pra mim dentro do universo de Marketing. Apesar de ter esse foco desde então, somente de 2018 pra cá eu realmente me envolvi em uma comunidade que nascia para trocar conhecimento sobre Marketing de Produto.

Estar nessa comunidade, conhecer outros profissionais e ver que havia um movimento de cada vez mais ter ofertas de vagas para Product Marketing que me estimulou a acompanhar essas ofertas. 

Esse meu envolvimento me levou não só a muitas conversas com profissionais de diferentes empresas que gostaria de implementar a competência de Marketing de Produto, mas também conversar com pessoas de outras áreas interessadas em fazer essa migração de carreira.

Inspirado em iniciativas como a [Elixir Radar](https://elixir-radar.com/){:target="_blank"} onde é possível encontrar vagas para trabalhar com a linguagem de programação Elixir, resolvi criar aqui uma lista de vagas para Product Marketing.

## Vagas {#vagas-product-marketing}

{% if site.data.job %}
<ul>
   {% for job in paginator.site.data.job %}
        <li style="list-style: none;">
            <p style="margin: 0; font-size: 1.5em"><a href="{{ job.url }}" onclick="analytics.track('clicked-job-{{ job.track }}')" target="_blank">{{ job.title }}</a></p>
            <p style="margin: 0; font-size: 0.85em;">{{ job.location }}</p>
            <p style="margin: 0; font-size: 0.85em;">{{ job.date }}</p>
        </li>
    <hr>
    {% endfor %}
</ul>
{% endif %}

{% if paginator.total_pages > 1 %}
  <div class="pagination">
    {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path | prepend: site.baseurl | replace: '//', '/' }}" class="button" >
      <i class="fa fa-chevron-left"></i>
      {{ site.theme_settings.str_prev }}
    </a>
    {% endif %}
    {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path | prepend: site.baseurl | replace: '//', '/' }}" class="button" >
      {{ site.theme_settings.str_next }}
      <i class="fa fa-chevron-right"></i>
    </a>
    {% endif %}
  </div>
{% endif %}