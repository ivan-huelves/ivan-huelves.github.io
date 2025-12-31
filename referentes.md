---
layout: page
title: Marco de referencia
permalink: /referentes/
---

Análisis de referentes clasificados en el marco de mi investigación doctoral.

---

### Explorar por Función
<div class="nav-links">
<p>
<a href="/etiquetas/accesibilidad/">Accesibilidad</a>
<a href="/etiquetas/exploracion-formal-y-o-performativa/">Exploración formal</a>
<a href="/etiquetas/expresion-paralinguistica/">Expresión paralingüística</a>
<a href="/etiquetas/identidad-visual/">Identidad visual</a>
<a href="/etiquetas/sistema-de-diseno-tipografico/">Sistemas de diseño</a>
<a href="/etiquetas/visualizacion-de-datos/">Visualización de datos</a>
<a href="/etiquetas/narrativa-social/">Narrativa social</a>
</p>
</div>

### Explorar por Contexto
<div class="nav-links">
<p>
<a href="/etiquetas/branding/">Branding</a>
<a href="/etiquetas/instalacion-artistica/">Instalación artística</a>
<a href="/etiquetas/investigacion-experimental/">Investigación / Experimental</a>
<a href="/etiquetas/producto-digital/">Producto digital</a>
<a href="/etiquetas/materializacion-fisica/">Materialización física</a>
</p>
</div>

### Explorar por Interacción y Tecnología (NUEVO)
<div class="nav-links">
<p>
<a href="/etiquetas/inteligencia-artificial/">Inteligencia Artificial</a>
<a href="/etiquetas/generativo/">Generativo</a>
<a href="/etiquetas/gestual/">Gestual</a>
<a href="/etiquetas/sonido/">Sonido / Voz</a>
<a href="/etiquetas/realidad-aumentada/">Realidad Aumentada</a>
<a href="/etiquetas/tipografia-variable/">Tipografía Variable</a>
<a href="/etiquetas/interactivo-multimodal/">Multimodal</a>
</p>
</div>

---

### Referentes analizados

<div class="project-grid">
  {% for proyecto in site.referentes %}
    <a href="{{ proyecto.url }}" class="project-card">
      
      <div class="card-image">
        {% if proyecto.thumbnail and proyecto.thumbnail != "" %}
          <img src="{{ proyecto.thumbnail }}" alt="Imagen de {{ proyecto.title }}" loading="lazy">
        {% else %}
          <div style="width:100%; height:150px; background-color: #f4f4f4; display:flex; align-items:center; justify-content:center; color:#999; font-size: 0.8em;">
            Sin Previsualización
          </div>
        {% endif %}
      </div>

      <div class="card-content">
        <span class="card-title" style="display:block; font-weight:bold; margin-bottom:0.5rem;">
            {{ proyecto.title }}
        </span>
        <div class="card-meta" style="font-size: 0.9em; color: #666;">
          {{ proyecto.author }}
          <br>
          <span style="color: #999;">{{ proyecto.year }}</span>
        </div>
      </div>

    </a>
  {% endfor %}
</div>