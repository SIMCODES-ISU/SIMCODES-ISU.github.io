---
title: Mentors
layout: default
permalink: /mentors/
---
<link rel="stylesheet" href="{{ site.assets.css }}">

Meet the mentors for the upcoming and past SIMCODES REU programs.

# 2026 Mentors

<div class="thumbnail-grid">
  {% assign filtered_mentors = site.mentors | where_exp:"item", "item.tags contains '2026'" %} 
  {% for post in filtered_mentors %}
    <div class="thumbnail-item">
      <a href="{{ post.url }}">
        <img src="{{ post.image.thumbnail }}" alt="{{ post.title }}">
        <h3>{{ post.title }}</h3>
      </a>
    </div>
  {% endfor %}
</div>

# 2025 Mentors

<div class="thumbnail-grid">
  {% assign filtered_mentors = site.mentors | where_exp:"item", "item.tags contains '2025'" %} 
  {% for post in filtered_mentors %}
    <div class="thumbnail-item">
      <a href="{{ post.url }}">
        <img src="{{ post.image.thumbnail }}" alt="{{ post.title }}">
        <h3>{{ post.title }}</h3>
      </a>
    </div>
  {% endfor %}
</div>
