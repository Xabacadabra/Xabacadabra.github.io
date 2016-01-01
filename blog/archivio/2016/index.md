---
layout: archive
title: "2016"
date: 2016-1-1
modified: 2016-1-1
excerpt: "Tutti i post del 2016."
feature:
  visible: true
  headline: "2016"
  category: "2016"
---
<div class="tiles">
{% for post in site.categories.2016 %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
