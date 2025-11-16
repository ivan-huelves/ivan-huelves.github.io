---
layout: page
title: Catálogo de Referentes
permalink: /referentes/
---

Aquí encontrarás una recopilación de referentes clasificados de mi tesis doctoral.

<ul>
  {% for proyecto in site.referentes %}
    <li>
      <a href="{{ proyecto.url }}">
        <strong>{{ proyecto.title }}</strong>
      </a> 
      - <em>{{ proyecto.author }} ({{ proyecto.year }})</em>
      <br>
      <small>{{ proyecto.tech }}</small>
    </li>
  {% endfor %}
</ul>
