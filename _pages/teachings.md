---
layout: page
title: teaching
permalink: /teachings/
description: 
nav: true
display_categories: [current courses, previous courses]
horizontal: false
---
<div class="row">
  <div class="col-md-8">
   <p indent="2em">
   I enjoy teaching because each class feels like a shared adventure; we’re explorers learning side by side, and my students’ questions keep my own curiosity vibrant while fostering a warm, inclusive atmosphere. For me, <it>being-in-the-classroom</it> is an existential practice—it allows me to dwell in what Heidegger calls the “authentic experience,” the stance in which we at bottom are able to own up to ourselves.
   <!-- (Basic Problems of Phenomenology, p. 160) -->
  <br>
   Below is a list of the current and some of my previous courses:
  <br>
   </p>
  </div>
  <div class="col-md-4">
    {% include figure.html path="/assets/img/teaching-prof.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<!-- pages/teachings.md -->
<div class="teachings">
{%- if site.enable_teaching_categories and page.display_categories %}
  <!-- Display categorized teachings -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_teachings = site.teachings | where: "category", category -%}
  {%- assign sorted_teachings = categorized_teachings | sort: "importance" %}
  <!-- Generate cards for each teaching -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for teaching in sorted_teachings -%}
      {% include teachings_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for teaching in sorted_teachings -%}
      {% include teachings.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display teachings without categories -->
  {%- assign sorted_teachings = site.teachings | sort: "importance" -%}
  <!-- Generate cards for each teaching -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for teaching in sorted_teachings -%}
      {% include teachings_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for teaching in sorted_teachings -%}
      {% include teachings.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
