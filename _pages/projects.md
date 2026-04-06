---
layout: page
title: research
permalink: /projects/
description: A glance at some of my recent research tracks
nav: true
display_categories: [current research tracks]
horizontal: false
---

<figure>
<center>
  <img src="/assets/img/projects/main.png" alt="Main Research Tracks" width="350"/>
  <!-- <figcaption>Main Research Tracks</figcaption> -->
</center>
</figure>

My research lies at the intersection of control and estimation theory, machine learning, and applied mathematics, with a focus on data-driven decision-making in complex and uncertain systems. A central theme of my work is the use of geometric structure to design learning and optimization algorithms, particularly from data pertinent to dynamical systems. With the rapid advancement of AI, there is a growing need for methods that can perform online data assimilation and decision-making under increasingly stringent performance and reliability requirements.

My work explores topics such as policy optimization on nonlinear manifolds, reinforcement learning, multi-agent coordination, and learning-based control without relying on fully known system models. The overarching objective is to develop principled and scalable algorithms that can operate reliably in real-world settings where uncertainty and structure are intrinsic. More broadly, this direction aims toward what I describe as trustworthy AI—ensuring that learning-enabled systems are robust, interpretable, and suitable for safety-critical applications such as autonomous systems and advanced mobility.

<!-- pages/projects.md -->
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
    <div class="row row-cols-2">
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
    <div class="row row-cols-2">
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
