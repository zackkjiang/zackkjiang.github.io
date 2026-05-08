\---

layout: page
title: projects
permalink: /projects/
description: Intelligent Sensing + AI Agent Applications across health, sport, mobility, and rehabilitation.
nav: true
nav\_order: 4
display\_categories: \[Rehabilitation, Cardiac Monitoring, Sport Interface, Dashcam AI, AI Agent]
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

<!-- pages/projects.md -->

<div class="projects">
{% if page.display\\\_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display\\\_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized\\\_projects = site.projects | where: "category", category %}
  {% assign sorted\\\_projects = categorized\\\_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted\\\_projects %}
      {% include projects\\\_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted\\\_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}
{% else %}
<!-- Display projects without categories -->
{% assign sorted\\\_projects = site.projects | sort: "importance" %}
  <!-- Generate cards for each project -->
{% if page.horizontal %}
<div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted\\\_projects %}
      {% include projects\\\_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted\\\_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>


