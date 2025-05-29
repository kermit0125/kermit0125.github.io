---
layout: archive
title: "学习经历 / Courses"
permalink: /courses/
author_profile: true
---

{% include base_path %}

<ul>
  {% for post in site.courses reversed %}
    <li>
      <strong>{{ post.title }}</strong> ({{ post.semester }})<br>
      <em>{{ post.description }}</em><br>
      🔑 Keywords: {{ post.keywords | join: ", " }}<br>
      📘 Project: {{ post.project }}
    </li>
    <br>
  {% endfor %}
</ul>
