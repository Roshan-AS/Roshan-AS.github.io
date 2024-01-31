---
layout: page
title: Teaching
permalink: /teaching/
description: List of Classes
nav: true
nav_order: 2
horizontal: false
---

<!-- pages/teaching.md -->
<div class="teaching`">
<!-- Display classes without categories -->
{%- assign sorted_classes = site.teaching | sort: "importance" -%}
<!-- Generate cards for each class -->
{% if page.horizontal -%}
<div class="container">
<div class="row row-cols-2">
{%- for class in sorted_classes -%}
  {% include teaching_horizontal.html %}
{%- endfor %}
</div>
</div>
{%- else -%}
<div class="grid">
{%- for class in sorted_classes -%}
  {% include teaching.html %}
{%- endfor %}
</div>
{%- endif -%}
</div>