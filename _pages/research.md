---
layout: page
title: Research lab
permalink: https://wires-ub.github.io
nav: true
nav_order: 1
dropwdown: false
horizontal: true
# children:
#     - title: Wireless Navigation
#       permalink: /research/localization/
#     - title: Robotic Automation
#       permalink: /research/robotics/
#     - title: Digital-Twins
#       permalink: /research/perception/
#     - title: Privacy in Sensing
#       permalink: /research/privacy/
---

<!-- pages/projects.md -->
I like to work on <b>DEPLOYABLE</b> wireless systems that can aid moder-day applications ranging from XR, Automation, IoT, etc.
The following are a group of projects that I am generally excited to work in using Wireless Systems.

<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-1">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-1">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>