---
layout: page
title: teaching
permalink: /teachings/
description: 
nav: true
display_categories: [current courses, previous courses]
horizontal: false
---

<p indent="2em">
  I love teaching because every class feels like a shared journey—we’re discovering ideas together, and my students’ questions constantly renew my own curiosity. I strive to create a warm, inclusive atmosphere where learning is not just about answers but about exploration. For me, being in the classroom is more than teaching—it’s a meaningful practice that opens the door to what Heidegger calls “authentic experience”: a way of engaging where we connect deeply with ideas, with one another, and with ourselves as learners; or in his words, "the stance in which we at bottom are able to own up to ourselves."
  <!-- (Basic Problems of Phenomenology, p. 160) -->
  <br>
  Below is a list of the current and some of my previous courses:
  <br>
</p>


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
