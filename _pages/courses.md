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
      <strong><a href="{{ course.url }}">{{ course.title }}</a> ({{ course.semester_range }})</strong>
      <ul>
        {% for c in course.courses %}
          <li>• {{ c.code }} - {{ c.name }}</li>
        {% endfor %}
      </ul>
    </li>
  {% endfor %}
</ul>
