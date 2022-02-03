---
layout: section 
title: Imersão 
url: sections/motivos
desc: Aquele que tem um 'por quê' pode suportar qualquer 'como'. Vamos explorar alguns motivos para se aprender línguas e como manter a motivação. 
---

## Artigos nesta seção 

2. Imersão
    - O que *exatamente* é imersão
    - Formas específicas de praticar a imersão
    - Formas de estudar para facilitar a imersão

{% for tag in site.tags %}
{% if tag[0] == "motivos" %}
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endif %}
{% endfor %}
