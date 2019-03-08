---
layout: post
title: Como eu falhei em um teste e isso ainda me incomoda
author: Felipe Barbosa
permalink: /como-falhei-teste/
categories: data
---

No mundo do empreendedorismo e startups se fala muito sobre falhar. É um tema que tem uma certa mística.

Eu já falei sobre esse assunto no post [Startup Fail](https://www.felipebarbosa.me/route-startup-fail/).

Mas muitas vezes as falhas vem em momentos da nossa carreira profissional e dois posts que li esses dias me fizeram lembrar um caso que eu deixei uma oportunidade muito legal escapar.

Um dos posts é um artigo que li no blog do FreeCodeCamp com o título [How I applied lessons learned from a failed technical interview to get 5 job offers](https://medium.freecodecamp.org/how-i-applied-lessons-learned-from-a-failed-technical-interview-to-get-5-job-offers-656fcf58034d). 

O outro foi uma [postagem no LinkedIn de um Data Scientist](https://www.linkedin.com/feed/update/urn:li:activity:6372092606968578048) que eu sigo e falava sobre a frustração de perder uma oportunidade e usar isso como maneira de melhorar as habilidades que faltaram.

Sempre se fala que o melhor é falhar rápido para aprender rápido, então vou revisitar o meu teste e explicar o que faria melhor e diferente.

Mas isso não quer dizer que minha análise agora está 100% correta, mas certamente estará muito acima do que eu fiz na época do teste.

## O Teste - Parte 1

Esse teste eu fiz para uma vaga em uma Startup brasileira bem legal que estava procurando alguém para trabalhar no time de produto focado em análise e performance.

Eu já havia conversado com o CEO da Startup alguns anos antes e, quando surgiu essa vaga, uma recomendação de um amigo em comum nos fez entrar em contato novamente.

Após algumas rodadas de conversas bem legais chegou o momento do teste.

Eu já estava acostumado com esse fluxo, quando entrei pro [Route](https://route.to) eu passei por uma fase onde realizei alguns testes. 

Confesso que estava um pouco nervoso para essa etapa pois, diferente da época do meu teste no Route, eu estava tentando uma vaga para uma área que exigiria um conhecimento mais técnico em análises e uso de ferramentas para tal.

Estava confiante porque acreditava que minha experiência com o Route e [Umbler](https://umbler.com) haviam me dado uma boa base de trabalhar com produto e marketing.

Por outro lado, estava nervoso porque a parte mais técnica eu sabia que precisava melhorar em alguns pontos.

Sempre me senti confortável para trabalhar com métricas, analisar o desempenho e performance dos produtos e campanhas que eu estava envolvido mas sabia que essa vaga em questão seria um desafio novo.

## O Teste - Parte 2

O teste foi feito pelo Skype. Eu teria um tempo para analisar umas informações em um cenário de uma empresa fictícia.

Levaria entre 30 e 45 minutos.

Do momento que começou até o fim foi tudo ladeira abaixo.

Esse era o teste em questão:

**Question 1: Financial Modeling and Other Analytics**

Facts:

- Developer ABC sells e-cards via its FB platform application, ABC’s eCards, at $5 per card
- Users on FB are 10MM at EOY 2009 and expected to grow 10% each year thereafter
- ABC’s traffic is 10% of FB’s platform users at EOY 2009 and expected to grow 5% each year thereafter
- ABC’s conversion (rate of purchase) is 0.5% of users
- ABC’s only costs are server operations of $10K per year plus $0.01 per card sold and payment fees via Paypal of 5% per card sold 
- ABC pays no taxes, and its cost of capital is 15%

Questions:

(a)	Please give a concise picture of ABC’s financial operations for the next 5 years (2010-2014). If continuing operations for the next 5 years requires a $62K upfront investment, would you recommend that they continue operating or not?  
(b)	Facebook decides to offer a competing payments product that charges 10% per card sold. How much increased conversion does ABC need to experience in order to switch from carrying PayPal to FB Payments?
(c)	In order to improve its performance, ABC decides to run an ad campaign on FB for its cards. Assuming each ad click has a 50% likelihood of leading to a purchase, what CPC(Cost per Click) should ABC be willing to pay? 
Please note that (c) is independent of (b).

Quando li o teste por cima vi que eu estava com problemas.

Apesar de ter feito análises da performance do Route, eram bem simples. Cabia a mim analisar coisas como CAC, LTV, os canais que mais convertiam, os usuários que mais avançavam no funil e sua origem.

Nunca havia precisado fazer uma análise financeira do negócio. Era um assunto que não passava pelas equipes que trabalhei.

Nós tínhamos a preocupação de gerar receita, tentar ver os melhores canais, calcular as métricas que falei acima, mas era uma outra pegada.

Sei lá, quando vi o teste parecia que estava naquela prova de matemática que tu não sabe se vai conseguir ir muito bem.

Entende algumas coisas, outras acha que sabe o caminho e faz tudo vendo onde irá chegar.

Tirei algumas dúvidas antes de começar e o relógio começou a rodar.

## Que comecem os jogos

Meu primeiro erro foi reescrever cada item de informação e o que deveria ser feito em um caderno.

Na hora achei que ao escrever as ideias iriam fluir, os pontos começariam a serem ligados e ficaria tudo mais simples.

No fim do tempo eu vi que essa minha decisão só me fez perder um tempo precioso para fazer as análises.

Eu poderia muito bem ter ido direto para o primeiro item.

Um detalhe do teste é que, apesar de não ser obrigatório, o uso do Excel era algo encorajado.

Não sou expert no Excel, sei algumas funcionalidades mas, como não uso no dia a dia para análises como as do teste, vi que precisaria de um tempo para me ambientar.

Ter perdido tempo no início ao escrever no papel o que já estava pronto, se mostrou mais uma vez um erro.

Outro ponto que vejo que errei foi não fazer mais perguntas antes de começar.

Não havia nada me impedindo de tirar mais dúvidas das coisas que eu não tinha tanta certeza. 

Então, depois de perder quase uns 10 minutos repassando as questões, comecei a resolver o problema apresentado na primeira questão.

## Questão A - Operações Financeiras da ABC 

Eu precisava analisar as finanças da ABC de 2010 até 2014, verificar como estava e se valia a pena mantê-la caso um investimento adiantado de $62K fosse necessário.

Comecei criando uma tabela para organizar as informações que eu tinha e começar os cálculos.

Nela coloquei nas colunas os anos e nas linhas os itens que estavam na descrição do cenário. A minha tabela inicial ficou da seguinte maneira:

<iframe class="airtable-embed" src="https://airtable.com/embed/shrBpjcZdt2TpC3I6?backgroundColor=blue&viewControls=on" frameborder="0" onmousewheel="" width="100%" height="533" style="background: transparent; border: 1px solid #ccc;"></iframe>

Comecei a preencher a linha dedicada ao Facebook. Mais precisamente ao tráfego projetado nesse período. Fiz isso porque era a partir dele que eu iria pegar o tráfego projetado para a ABC.

Eu estava com dúvida sobre o que significava o EOY e fiz uma pesquisa rápida. O que eu entendi é que no fim de 2009 o tráfego foi de 10MM e a cada ano era esperado crescer 10%.

Na hora deveria ter criado uma fórmula no Excel para resolver quanto seria o crescimento ano após ano levando em conta os 10%, mas fiz as contas de cabeça. Outro erro que me custou muito tempo.

Sabia que o tráfego da ABC no EOY de 2009 foi 10% mas que cresceria 5% a cada ano.

Nesse ponto fiquei com uma dúvida sobre essa informação. 

O cenário indicava que no primeiro ano era os 10% do tráfego de 2009 e depois iria aumentando em 5% relativo ao tráfego do Facebook (15% em 2010, 20% em 2011...) ou seria os 10% de 20099 e a partir dele iria aumentar a cada ano 5%?

Eu acabei optando pelo segundo cenário mas, pensando bem, não fazia muito sentido.

A informação só falava do aumento de 5% do tráfego a partir de 2009 e não que o aumento do tráfego vindo do Facebook iria aumentar.

Obviamente,tendo entendido o cenário de maneira equivocada isso afetou toda minha análise. 

Enfim, continuando.

Com a informação do tráfego calculada, com a taxa de conversão do tráfego em pagantes e com o valor por cartão eu poderia ter a informação de quanto eles estavam gerando com as vendas.

Com a quantidade vendida teria a informação dos custos atrelados as vendas e com isso ver quanto ficaria a receita para poder responder se valia a pena a operação mesmo investindo $62K.

<iframe class="airtable-embed" src="https://airtable.com/embed/shricKWpxqkzra68i?backgroundColor=blue&viewControls=on" frameborder="0" onmousewheel="" width="100%" height="533" style="background: transparent; border: 1px solid #ccc;"></iframe>

Tudo certo, não é mesmo?

Errado. Tinha a informação do Custo de Capital de 15% e eu não tinha nem ideia do que fazer com ela.

Na hora não tinha tempo de pesquisar o que significava aquele dado. Mas lendo alguns artigos (como [esse](https://www.investopedia.com/terms/c/costofcapital.asp) e [esse](https://hbr.org/2015/04/a-refresher-on-cost-of-capital) encontrei que o Custo de Capital é:

> É o retorno necessário para fazer um investimento em um projeto valer a pena.

Com essa informação entendo que seria preciso um retorno de 15%, em relação aos $62K investidos, nos próximos 5 anos para valer a pena continuar a operação.

Então, valeria a pena continuar no negócio?

De 2010 até 2014 a ABC teria gerado um resultado de $86.345, o que dá por volta de 39% de retorno. Eu recomendaria eles continuarem.

## Questão B - PayPal x Facebook

Essa questão pedia uma análise sobre quanto deveria aumentar a conversão para valer a pena trocar do PayPal que cobrava 5% de cada cartão vendido pro Facebook que cobraria 10%.

<iframe class="airtable-embed" src="https://airtable.com/embed/shrEltfU0wr9jmYXK?backgroundColor=blue&viewControls=on" frameborder="0" onmousewheel="" width="100%" height="533" style="background: transparent; border: 1px solid #ccc;"></iframe>

Nessa tabela, eu fiz um teste aumentando de 0,5% de conversão para 0,6% de conversão e ver o resultado financeiro.

Esse aumento é de 20% nas conversões. 

No dia do teste eu já havia perdido muito tempo em coisas sem tanta importância e cheguei nesse ponto na correria.

Eu tinha perdido muito tempo na questão de letra a.

Então eu simplesmente respondi que ir para 1% de conversão já ajudaria. Sem comentários.

Claro que ir pra 1% traria uma grande receita, mas o aumento percentual nesse caso seria de 100%!

Quem consegue isso facilmente?

Até mesmo um aumento de 20% já pode ser desafiador.

Eu completei a resposta dizendo que outros fatores podem influenciar na troca. Porque mesmo com esse aumento eu só trocaria se fosse realmente um produto melhor do que o PayPal.

Esse tipo de informação não tem no exercício mas acho que é algo que deveria ser levado em conta.
 
## Questão C - Qual o CPC aceitável para valer a pena a campanha no Facebook?

Aparentemente, essa questão era a mais simples.

O problema é que quando fui resolver ela eu já tinha recebido o aviso de que meu tempo estava acabando.

Não tinha muito tempo para pensar a questão e o que fiz foi resolver de cabeça com a seguinte ideia:

**O valor do cartão é $5. Quem clica no anúncio tem 50% de efetuar a compra. Só aceitaria pagar, no máximo, metade do valor do cartão, ou seja, $2,50**.

Parece razoável essa ideia, mas na verdade teria que ser menos que esse valor.

Pagando $2,50 por clique, com 50% para efetuar a compra e sem saber qual é o ticket médio, com o valor de $5 significa que a toda compra iria apenas cobrir os custos do anúncio.

Isso ocorre porque 2 pessoas precisariam clicar para 1 comprar.

Esses dois cliques custariam o mesmo valor gerado.

Tempos depois desse teste e revisitando o que eu fiz, acho que é razoável essa linha de pensamento.

O grande problema do que coloquei no teste é que não desenvolvi e nem expliquei de maneira robusta porque eu estava colocando o limite escolhido no cpc.

## O que aprendi com essa história?

A primeira coisa foi saber que preciso me preparar melhor para lidar com testes nesse estilo.

Certamente, se for participar de alguma seleção para uma vaga mais de análise irei antecipar que um teste nesse estilo irá surgir.

Mais ou menos como desenvolvedores se preparam para as famosas entrevistas onde é preciso resolver algum caso em um quadro branco.

Diria que todo desenvolvedor sabe que isso irá acontecer durante uma seleção.

A segunda foi que eu vi que precisava levar meu conhecimento de análises e utilização do Excel e de ferramentas de análise para um outro nível.

Algo além dos cenários mais comuns de marketing digital.

Não que eu vá passar todo dia por situações como a análise desse cenário do teste mas para estimular o pensamento analítico de outra forma.

Comecei a investir mais nos treinamentos de sites como [Datacamp](https://datacamp.com) e [Dataquest](https://dataquest.io), acompanhar profissionais na área de Data Science no LinkedIn e me motivei a aprender mais profundamente a ferramenta que todo mundo sabe que é importantíssima para análises: Microsoft Excel.

Sabia que eu estava em um nível próximo ao intermediário, mas agora quero me estabelecer no intermediário para chegar logo no avançado.

Resolvi me tornar mais fluente na parte de análise de produtos e de negócios.

Não que eu queira ir para uma dessas áreas de ciência de dados, esse teste está longe de ter uma complexidade nesse nível.

Mas eu sinto falta da vivência desse pensamento mais matemático. Durante meus anos no Route era mais próximo do meu trabalho, mas hoje está um pouco mais distante.

E a prática vai levando a melhorias contínuas nas análises e como entender os problemas. 

Acrescentar novos conhecimentos e ferramentas a algo que eu sempre me senti confortável em fazer.

## E o que não aprendi?

Ainda não aprendi a resolver esse teste com 100% de confiança que meu raciocínio e desenvolvimento agora está correto.

Por favor, destrua ele se for o caso.

Mas quero chegar na resposta definitiva. 


