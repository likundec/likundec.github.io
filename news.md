---
layout: archive
title: "News"
date: 2014-05-30T11:40:45-04:00
modified:
excerpt: "A news gallery of research, projects, and work progress."
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.news %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles --> 