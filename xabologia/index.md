---
layout: archive
title: "Xabologia"
date: 2015-12-19
modified: 2015-12-19
excerpt: "blabla."
feature:
  visible: true
  headline: "Featured Articles"
  category: xabologia
---

{% for post in site.categories.articles %}
  {% if post.featured != true %}
  {% include archive__item.html %}
  {% endif %}
{% endfor %}
