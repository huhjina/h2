---
title: Team
nav:
  order: 3
  tooltip: About our team
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<div class="portrait-list">
  {% assign sorted_members = site.members | sort: "name" %}
  {% for member in sorted_members %}
    {% include portrait.html member=member %}
  {% endfor %}
</div>
