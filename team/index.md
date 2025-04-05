---
title: Team
nav:
  order: 3
  tooltip: About our team
---


Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<div class="portrait-list" style="display: flex; flex-wrap: wrap; gap: 2rem; justify-content: center;">
  {% assign sorted_members = site.members | sort: "name" %}
  {% for member in sorted_members %}
    <div class="portrait-wrapper">
      <a href="{{ member.url | relative_url }}" class="portrait" aria-label="{{ member.name }}">
        <img
          src="{{ member.image | relative_url }}"
          class="portrait-image"
          alt="{{ member.name }}"
          style="width: 150px; height: 150px; object-fit: cover; border-radius: 50%; margin-bottom: 0.5rem;"
        />
        <span class="portrait-name">{{ member.name }}</span>
        {% if member.role %}
          <span class="portrait-description">{{ member.role }}</span>
        {% endif %}
      </a>
    </div>
  {% endfor %}
</div>
