---
layout: project_type
title: "Project Type: Past"
description: "Past PaCT Lab Projects"
pagination: 
  enabled: true
  collection: all
  category: Past
---
{% for post in paginator.posts %}
  {% include portfolio_item.html %}
{% endfor %}