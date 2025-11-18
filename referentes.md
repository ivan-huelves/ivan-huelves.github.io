---
layout: page
title: Marco de referencia
permalink: /referentes/
---

Análisis de referentes clasificados en el marco de mi investigación doctoral.

---

### 🧭 Explorar por Función

<div class="nav-links">
<p>
<a href="/etiquetas/accesibilidad/">Accesibilidad</a>
<a href="/etiquetas/exploracion-formal-y-o-performativa/">Exploración formal y/o performativa</a>
<a href="/etiquetas/expresion-paralinguistica/">Expresión paralingüística</a>
<a href="/etiquetas/identidad-visual/">Identidad visual</a>
<a href="/etiquetas/sistema-de-diseno-tipografico/">Sistema de diseño tipográfico</a>
<a href="/etiquetas/visualizacion-de-datos/">Visualización de datos</a>
<a href="/etiquetas/narrativa-social/">Narrativa social</a>
</p>
</div>

### 🧭 Explorar por Contexto

<div class="nav-links">
<p>
<a href="/etiquetas/branding/">Branding</a>
<a href="/etiquetas/instalacion-artistica/">Instalación artística</a>
<a href="/etiquetas/investigacion-experimental/">Investigación / Experimental</a>
<a href="/etiquetas/producto-digital/">Producto digital</a>
</p>
</div>

### 🧭 Explorar por Grado de interactividad

<div class="nav-links">
<p>
<a href="/etiquetas/reactivo/">Reactivo</a>
<a href="/etiquetas/interactivo/">Interactivo</a>
<a href="/etiquetas/interactivo-multimodal/">Interactivo multimodal</a>
<a href="/etiquetas/generativo/">Generativo</a>
</p>
</div>

---

### 📚 Catálogo Completo

<div class="project-grid">
  {% for proyecto in site.referentes %}
    <a href="{{ proyecto.url }}" class="project-card">
      
      <div class="card-image">
        {% if proyecto.thumbnail != "" %}
          <img src="{{ proyecto.thumbnail }}" alt="Imagen de {{ proyecto.title }}" loading="lazy">
        {% else %}
          <div style="width:100%; height:100%; display:flex; align-items:center; justify-content:center; color:#ccc;">
            Sin Imagen
          </div>
        {% endif %}
      </div>

      <div class="card-content">
        <span class="card-title">{{ proyecto.title }}</span>
        <div class="card-meta">
          {{ proyecto.author }} ({{ proyecto.year }})
          <br>
          <span style="font-size: 0.85em; color: #999;">{{ proyecto.tech }}</span>
        </div>
      </div>

    </a>
  {% endfor %}
</div>
