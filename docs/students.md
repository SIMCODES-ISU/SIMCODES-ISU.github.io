---
title: Students
layout: default
permalink: /students/
---
<link rel="stylesheet" href="{{ site.assets.css }}">

Meet the aspiring interns who are part of the SIMCODES program — exploring, 
building, and growing through hands-on learning.

# 2026 Cohort

<div class="thumbnail-grid">
  {% for post in site.students-2026 %}
    <div class="thumbnail-item">
      <a href="{{ post.url }}">
        <img src="{{ post.image.thumbnail }}" alt="{{ post.title }}">
        <h3>{{ post.title }}</h3>
      </a>
    </div>
  {% endfor %}
</div>


# 2025 Cohort 

<div class="thumbnail-grid">
  {% for post in site.students-2025 %}
    <div class="thumbnail-item">
      <a href="{{ post.url }}">
        <img src="{{ post.image.thumbnail }}" alt="{{ post.title }}">
        <h3>{{ post.title }}</h3>
      </a>
    </div>
  {% endfor %}
</div>