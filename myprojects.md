---
layout: default
title: "My Projects"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="My Projects" %}
{% endif %}