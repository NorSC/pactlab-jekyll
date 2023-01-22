---
layout: project_type
title: "Project Type: Current"
description: "Current PaCT Lab Projects"
pagination: 
  enabled: true
  collection: all
  category: Current
---
{% for post in paginator.posts %}
  {% include portfolio_item.html %}
{% endfor %}