---
layout: article
title: "visualization_Folder"
date: 2018-01-22T11:40:45-04:00
modified:
excerpt: "可视化作品集"
tags: []
image: 
  feature: 300x200.gif
  teaser:
---

期中作品展示

<div class="tiles">
{% for post in site.categories.SDG %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 SDG 的列出来-->