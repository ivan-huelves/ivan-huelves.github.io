---
layout: page
title: Marco de referencia
permalink: /referentes/
---

Referentes analizados en el marco de mi investigación doctoral.

---

### Explorar por Función

<p>
<a href="/etiquetas/accesibilidad/">Accesibilidad</a> | 
<a href="/etiquetas/exploracion-formal-y-o-performativa/">Exploración formal y/o performativa</a> | 
<a href="/etiquetas/expresion-paralinguistica/">Expresión paralingüística</a> | 
<a href="/etiquetas/identidad-visual/">Identidad visual</a> | 
<a href="/etiquetas/sistema-de-diseno-tipografico/">Sistema de diseño tipográfico</a> | 
<a href="/etiquetas/visualizacion-de-datos/">Visualización de datos</a> | 
<a href="/etiquetas/narrativa-social/">Narrativa social</a>
</p>

### Explorar por Contexto

<p>
<a href="/etiquetas/branding/">Branding</a> | 
<a href="/etiquetas/instalacion-artistica/">Instalación artística</a> | 
<a href="/etiquetas/investigacion-experimental/">Investigación / Experimental</a> | 
<a href="/etiquetas/producto-digital/">Producto digital</a>
</p>

### Explorar por Grado de interactividad

<p>
<a href="/etiquetas/reactivo/">Reactivo</a> | 
<a href="/etiquetas/interactivo/">Interactivo</a> | 
<a href="/etiquetas/interactivo-multimodal/">Interactivo multimodal</a> | 
<a href="/etiquetas/generativo/">Generativo</a>
</p>

---

### Todos los referentes analizados

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
