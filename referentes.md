---
layout: page
title: Marco de referencia
permalink: /referentes/
---

Aquí encontrarás una recopilación de referentes clasificados de mi tesis doctoral.

<ul>
  {% for proyecto in site.referentes %}
    <li>
      <a href="{{ proyecto.url }}">
        <strong>{{ proyecto.title }}</strong>
      </a> 
      - <div>{{ proyecto.author }} ({{ proyecto.year }})</div>
      <br>
      <small>{{ proyecto.tech }}</small>
    </li>
  {% endfor %}
</ul>
