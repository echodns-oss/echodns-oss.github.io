---
layout: default
title: By Essence
---

# Precepts by Essence

{% assign essences = site.precepts | group_by:"essence" %}
{% for group in essences %}
## {{ group.name }}
<ul>
  {% for precept in group.items %}
    <li><a href="{{ precept.url }}">{{ precept.title }}</a> ({{ precept.item }})</li>
  {% endfor %}
</ul>
{% endfor %}
