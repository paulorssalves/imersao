---
layout: section 
title: Método
url: sections/metodos
desc: Vamos por isso em prática. O processo se dá por meio do "cair-de-cabeça". Mas como podemos tornar esse "cair-de-cabeça" mais eficiente e agradável? 
---

3. A prática da repetição espaçada
    - Fundamentos da repetição espaçada
      - Memória de curto prazo e longo prazo
      - O esquecimento natural
    - Sistemas de repetição espaçada
      - Flashcards
    - Introdução ao Anki
      - Como criar um flashcard
      - Como criar múltiplos flashcards de uma só vez
      - Criando uma conta no AnkiWeb
      - Adicionando áudio aos flashcards: *AwesomeTTS* 
    - *Sentence mining*
  - Customização 
    - Como criar flashcards diferentes
    - Editando o estilo dos flashcards
      - HTML
      - CSS 

{% for tag in site.tags %}
{% if tag[0] == "metodo" %}
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endif %}
{% endfor %}
