---
title: Projects
layout: default
permalink: /projects/
---
<link rel="stylesheet" href="{{ site.assets.css }}">

Exciting Research Projects for Interns

# 2026 Projects

<div class="thumbnail-grid">
  {% assign filtered_projects = site.projects | where_exp:"item", "item.tags contains '2026'" %} 
  {% for post in filtered_projects %}
    <div class="thumbnail-item">
      <a href="{{ post.url }}">
        <img src="{{ post.image.thumbnail }}" alt="{{ post.title }}">
        <h3>{{ post.title }}</h3>
      </a>
    </div>
  {% endfor %}
</div>

# 2025 Projects

<div class="thumbnail-grid">
  {% assign filtered_projects = site.projects | where_exp:"item", "item.tags contains '2025'" %} 
  {% for post in filtered_projects %}
    <div class="thumbnail-item">
      <a href="{{ post.url }}">
        <img src="{{ post.image.thumbnail }}" alt="{{ post.title }}">
        <h3>{{ post.title }}</h3>
      </a>
    </div>
  {% endfor %}
</div>