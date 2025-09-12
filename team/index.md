---
title: Team
nav:
  order: 3
  tooltip: About our team
---

Our lab is an interdisciplinary team coming from computer science, electrical engineering, design, psychology, data science, and many other areas core to the field of human-computer interaction. 

<div class="portrait-list">
  {% assign sorted_members = site.members | sort: "name" %}
  {% for member in sorted_members %}
    {% include portrait.html member=member %}
  {% endfor %}
</div>
