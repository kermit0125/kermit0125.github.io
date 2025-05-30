{% assign sorted_courses = site.courses | sort: 'sort_order' %}
{% for course in sorted_courses %}
  <li>
    <strong>
      <a href="{{ course.url }}">{{ course.title_zh }} / {{ course.title }}</a>
      ({{ course.semester_range }})
    </strong>
    <ul>
      {% for c in course.courses %}
        <li>{{ c.code }} - {{ c.name_zh }} / {{ c.name }}</li>
      {% endfor %}
    </ul>
  </li>
{% endfor %}
