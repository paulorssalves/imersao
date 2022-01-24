---
layout: section 
title: Métodos
url: sections/metodos
desc: Vamos por isso em prática. O processo se dá por meio do "cair-de-cabeça". Mas como podemos tornar esse "cair-de-cabeça" mais eficiente e agradável? 
---

{% for tag in site.tags %}
{% if tag[0] == "metodo" %}
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endif %}
{% endfor %}
