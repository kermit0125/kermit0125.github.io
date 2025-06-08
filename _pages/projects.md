---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% assign sorted_categories = site.projects | map: "categories" | uniq | sort %}
{% for category in sorted_categories %}
  <h2 id="{{ category }}">{{ category }}</h2>
  {% assign posts = site.projects | where_exp:"item", "item.categories contains category" %}
  {% for post in posts %}
    - [{{ post.title }}]({{ post.url | relative_url }})
  {% endfor %}
{% endfor %}
