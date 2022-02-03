---
layout: post
title: Motivação 
desc: Há muitos equívocos a respeito do aprendizado de novas línguas. O processo é mais fácil (e divertido) do que parece, e nós vamos abordar isso aqui. 
url: sections/equivocos
---

## Temas
1. Motivação e Equívocos
    - O que esperar encontrar neste site. 
    - Por que aprender uma língua?
      - A importância de se ter um motivo
    - Traçando objetivos 
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
    - Começar a falar de fato 

{% for tag in site.tags %}
{% if tag[0] == "equivocos" %}
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endif %}
{% endfor %}
