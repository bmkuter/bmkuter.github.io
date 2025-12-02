---
layout: default
title: Welcome to My GitHub Page
---

# Welcome to My GitHub Page

## About Me

I'm a maker and developer passionate about IoT, automation, and creating solutions that bridge the physical and digital worlds.

## Latest Project Updates

Here are my current projects:

{% assign sorted_projects = site.data.projects | sort: 'last_updated' | reverse %}

<div class="projects-container">
{% for project in sorted_projects %}
  {% include project-card.html project=project %}
{% endfor %}
</div>

---

© 2025 Benjamin Kuter. All rights reserved.
