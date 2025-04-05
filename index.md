---
layout: default
title: Our Team
---

<h1 style="text-align: center;">Meet the Team</h1>

<div class="team-grid">
  {% for member in site.data.team %}
    <div class="team-member">
      <a href="#{{ member.name | slugify }}">
        <img src="/images/{{ member.image | default: 'placeholder.jpg' }}" alt="{{ member.name }}">
        <h3>{{ member.name }}</h3>
        <p>{{ member.role }}</p>
      </a>
    </div>
  {% endfor %}
</div>

<hr>

{% for member in site.data.team %}
  <div id="{{ member.name | slugify }}" class="team-detail">
    <h2>{{ member.name }}</h2>
    <img src="/images/{{ member.image | default: 'placeholder.jpg' }}" alt="{{ member.name }}" class="profile-pic">
    <p><strong>Role:</strong> {{ member.role }}</p>
    <p>{{ member.bio }}</p>
    {% if member.website %}
      <p><a href="{{ member.website }}" target="_blank">Visit Website</a></p>
    {% endif %}
    <hr>
  </div>
{% endfor %}
