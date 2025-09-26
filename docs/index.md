---
layout: page
title: Documentation
description: Everything you need to work with the Ancient Yolk Lore project.
permalink: /docs/
---
<p>Use these guides to install, configure, and extend the project. The sidebar inside each guide shows every available topic.</p>
<ul class="doc-list">
  {% assign docs = site.docs | sort: 'nav_order' %}
  {% for doc in docs %}
  <li>
    <h2><a href="{{ doc.url | relative_url }}">{{ doc.nav_title | default: doc.title }}</a></h2>
    {% if doc.summary %}<p>{{ doc.summary }}</p>{% endif %}
  </li>
  {% endfor %}
</ul>

