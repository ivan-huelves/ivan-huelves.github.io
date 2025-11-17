---
layout: page
title: Marco de referencia
permalink: /referentes/
---

Análisis de referentes clasificados en el marco de mi investigación doctoral.

<ul>
  {% for proyecto in site.referentes %}
    <li>
      <a href="{{ proyecto.url }}">
        <strong>{{ proyecto.title }}</strong>
      </a> 
      - <span>{{ proyecto.author }} ({{ proyecto.year }})</span>
      <br>
      <small>{{ proyecto.tech }}</small>
    </li>
  {% endfor %}
</ul>
