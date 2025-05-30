---
title: "课程总览"
layout: single
permalink: /courses/
author_profile: true
---

<style>
  .school-title {
    text-align: center;
    font-size: 1.5rem;
    margin: 2em 0 1em 0;
    font-weight: bold;
  }
</style>

{% assign sorted_courses = site.courses | sort: 'sort_order' %}

<div class="school-title">温州肯恩大学 / Wenzhou-Kean University</div>

{% for course in sorted_courses %}
  {% if course.sort_order <= 202199 %}
  <li>
    <strong>
      <a href="{{ course.url }}">{{ course.title_zh }} / {{ course.title }}</a> ({{ course.semester_range }})
    </strong>
    <ul>
      {% for c in course.courses %}
        <li>{{ c.code }} - {{ c.name_zh }} / {{ c.name }}</li>
      {% endfor %}
    </ul>
  </li>
  {% endif %}
{% endfor %}

<div class="school-title">美国东北大学 / Northeastern University</div>

{% for course in sorted_courses %}
  {% if course.sort_order > 202199 %}
  <li>
    <strong>
      <a href="{{ course.url }}">{{ course.title_zh }} / {{ course.title }}</a> ({{ course.semester_range }})
    </strong>
    <ul>
      {% for c in course.courses %}
        <li>{{ c.code }} - {{ c.name_zh }} / {{ c.name }}</li>
      {% endfor %}
    </ul>
  </li>
  {% endif %}
{% endfor %}
