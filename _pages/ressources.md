---
title: Ressources
permalink: /ressources
layout: default
---
{% for ressource in site.ressources %}
<h2>{{ ressource.title }}</h2>

{{ ressource.content }}
{% endfor %}