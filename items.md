---
layout: default
title: By Item
---

# Precepts by Item

{% assign items = site.precepts | group_by:"item" %}
{% for group in items %}
## {{ group.name }}
<ul>
  {% for precept in group.items %}
    <li><a href="{{ precept.url }}">{{ precept.title }}</a> ({{ precept.essence }})</li>
  {% endfor %}
</ul>
{% endfor %}
