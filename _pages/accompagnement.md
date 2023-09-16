---
title: Ressources
permalink: /accompagnement
layout: no-sidebar
image: 
image-alt: 
---
{% for ressource in site.ressources %}
{% if ressource.active != false %}
<h3><a href="{{ ressource.url | relative_url }}">{{ ressource.title }}</a></h3>
<p>Tonalité: {{ ressource.key }}</p>
<p>Type: {{ ressource.type }}</p>
<p>Niveau: {{ ressource.difficulty }}</p>
{% endif %}
{% endfor %}