---
layout: post
title: Equívocos 
desc: Há muitos equívocos a respeito do aprendizado de novas línguas. O processo é mais fácil (e divertido) do que parece, e nós vamos abordar isso aqui. 
url: sections/equivocos
---

{% for tag in site.tags %}
{% if tag[0] == "equivocos" %}
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endif %}
{% endfor %}
