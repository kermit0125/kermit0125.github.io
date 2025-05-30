---
layout: archive
title: "学习经历 / Courses"
permalink: /courses/
author_profile: true
---

{% include base_path %}

## 📘 所有学期

<ul>
  {% assign sorted_courses = site.courses | sort: 'title' %}
  {% for course in sorted_courses %}
    <li>
      <a href="{{ course.url }}">{{ course.title }} ({{ course.semester_range }})</a>
    </li>
  {% endfor %}
</ul>
