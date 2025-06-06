---
layout: page
title: Projects
permalink: /projects/
---

Here are some of my side projects, mods, and experiments. Click each for more info.

<div class="project-gallery">
  {% for project in site.projects %}
  <div class="project-tile">
    <img src="{{ project.image }}" alt="{{ project.title }}">
    <h3>{{ project.title }}</h3>
    <p>{{ project.description }}</p>
  </div>
  {% endfor %}
</div>
