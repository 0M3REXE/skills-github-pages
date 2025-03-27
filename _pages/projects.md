---
layout: default
title: Projects
permalink: /projects/
---

# My Projects

Explore some of my key technical projects and security assessments:

{% for project in site.projects %}
  {% include project-card.html %}
{% endfor %}