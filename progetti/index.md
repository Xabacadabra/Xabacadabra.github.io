---
layout: archive
title: "Progetti"
date: 2015-12-19
modified: 2015-12-19
excerpt: "(work in progress)"
feature:
  visible: true
  headline: "Featured Articles"
  category: progetti
---
<div class="tiles">
{% for post in site.categories.progetti %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
