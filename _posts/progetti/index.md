---
layout: archive
title: "Progetti"
date: 2015-12-19
modified: 2015-12-19
excerpt: "Cose mie."
feature:
  visible: true
  headline: "Featured Articles"
  category: articles
---

{% for post in site.categories.articles %}
  {% if post.featured != true %}
  {% include archive__item.html %}
  {% endif %}
{% endfor %}
