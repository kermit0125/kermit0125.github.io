---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% assign sorted_categories = "计算机视觉 / Computer Vision,图像生成 / Image Generation,数据可视化 / Data Visualization,数据分类 / Data Classification,其他 / Others" | split: "," %}
{% for category in sorted_categories %}
  <h2 id="{{ category }}">{{ category }}</h2>
  {% assign posts = site.projects | where_exp:"item", "item.categories contains category" %}
  {% for post in posts %}
  - [{{ post.title }}]({{ post.url | relative_url }})
  {% endfor %}
{% endfor %}
