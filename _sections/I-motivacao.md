---
layout: post
title: Motivação e equívocos
desc: Há muitos equívocos a respeito do aprendizado de novas línguas. O processo é mais fácil (e divertido) do que parece, e nós vamos abordar isso aqui. 
url: sections/equivocos
---

## Temas
- Motivação e Equívocos
    - O que esperar encontrar neste site. 
    - [X] Por que aprender uma língua?
      - [X] A importância de se ter um motivo
      - [X] Traçando objetivos 
    - Ansiedade e perfeccionismo
    - O afeto no aprendizado
    - A gramática e o seu papel 
    - Aprendizado e aquisição
        - O estudo e a imersão
        - Aprender uma língua é viver na língua
        - Confie no seu cérebro para fazer o trabalho
    - O papel do estudo no apoio à aquisição
      - O papel da aula no meio da aquisição
      - Cursos de idiomas
        - O benefício das escolas de idiomas -- das boas -- é o fator socialização. Há pessoas que sentem necessidade de socializar para tudo: fazer exercícios físicos, estudar, aprender idiomas etc. Se você não tem o perfil de fazer as coisas por conta própria e até mesmo de forma solitária, uma escola de idiomas pode ser a opção certa para você. Isso não quer dizer que você não pode se beneficiar do método aqui apresentado: pelo contrário: embora tudo o que aqui é apresentado funcione por si só, essas coisas também podem potencializar e ser potencializadas pela união a outros métodos. 
    - Começar a falar de fato 

{% for tag in site.tags %}
{% if tag[0] == "motivos" %}
  <ol>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ol>
{% endif %}
{% endfor %}
