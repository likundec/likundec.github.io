---
layout: archive
title: "Research"
date: 2014-05-30T11:40:45-04:00
modified:
excerpt: "An archive of portfolios, scientific studies, and research posts."
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.research %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->