---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

<div class="team-grid" style="display: flex; flex-wrap: wrap; gap: 2rem; justify-content: center;">
  {% assign sorted_members = site.members | sort: "name" %}
  {% for member in sorted_members %}
    <a href="{{ member.url | relative_url }}" style="text-align: center; text-decoration: none; color: inherit; width: 150px;">
      <div>
        <img src="/images/{{ member.image | default: 'placeholder.jpg' }}" alt="{{ member.name }}" style="width: 150px; height: 150px; object-fit: cover; border-radius: 50%; margin-bottom: 0.5rem;" />
        <strong>{{ member.name }}</strong><br/>
        {% if member.role %}
          <span style="font-size: 0.9rem;">{{ member.role }}</span>
        {% endif %}
      </div>
    </a>
  {% endfor %}
</div>



{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
<!-- Trigger rebuild -->

{% include section.html %}

<!-- Trigger rebuild -->
git commit --allow-empty -m "Trigger rebuild"
git push

<!-- Force rebuild -->
