---
layout: page
title: projects
permalink: /projects/
description: Intelligent Sensing + AI Agent Applications across health, sport, mobility, and rehabilitation.
nav: true
nav_order: 4
display_categories: [Rehabilitation, Cardiac Monitoring, Sport Interface, Dashcam AI, AI Agent]
horizontal: false
---

<style>
h2.category,
.projects h2.category {
  color: #b509ac !important;
  font-weight: 700 !important;
  opacity: 1 !important;
  margin-top: 2rem;
  margin-bottom: 1rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid #e0e0e0;
  font-size: 2rem;
}

.projects .card-img-top {
  max-width: 100%;
  width: auto;
  height: auto;
  max-height: 240px;
  display: block;
  margin: 0 auto;
}

.projects .card {
  height: 100%;
  text-align: center;
}

.projects .card-body {
  text-align: left;
}
</style>

<div class="projects">
{% if page.display_categories %}
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}
{% else %}
{% assign sorted_projects = site.projects | sort: "importance" %}
{% if page.horizontal %}
<div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>
