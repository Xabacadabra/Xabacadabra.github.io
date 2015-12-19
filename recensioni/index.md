---
layout: archive
title: "Recensioni"
date: 2015-12-19
modified: 2015-12-19
excerpt: "Se l'ho recensito, sta qui."
feature:
  visible: true
  headline: "Recensioni Top"
  category: recensioni
---

{% for post in site.categories.recensioni %}
  {% if post.featured != true %}
  {% include archive__item.html %}
  {% endif %}
{% endfor %}
