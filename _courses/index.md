---
title: "课程总览 / Course Overview"
layout: single
permalink: /courses/
author_profile: true
---

{% assign sorted_courses = site.courses | sort: 'sort_order' %}
<ul>
{% for course in sorted_courses %}
  <li>
    <strong>
      <a href="{{ course.url }}">{{ course.title_zh }} / {{ course.title }}</a>
      ({{ course.semester_range }})
    </strong>
    {% if course.courses %}
      <ul>
        {% for c in course.courses %}
          <li>{{ c.code }} - {{ c.name_zh }} / {{ c.name }}</li>
        {% endfor %}
      </ul>
    {% endif %}
  </li>
{% endfor %}
</ul>
