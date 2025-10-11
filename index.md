---
layout: default
title: Welcome to My GitHub Page
---

# Welcome to My GitHub Page

## About Me

I'm a maker and developer passionate about IoT, automation, and creating solutions that bridge the physical and digital worlds.

## Latest Project Updates

Here are my current projects - each one is an ongoing story of innovation and learning:

{% assign sorted_projects = site.data.projects | sort: 'last_updated' | reverse %}

<div class="projects-container">
{% for project in sorted_projects %}
  {% include project-card.html project=project %}
{% endfor %}
</div>

## Contact

Provide your contact information here.

---

© 2025 Benjamin Kuter. All rights reserved.
