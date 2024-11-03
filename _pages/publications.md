---
layout: page
permalink: /publications/
title: publications
description: in reversed chronological order. For an up-to-date list, please see my <a href='https://scholar.google.com/citations?user=39Jo6ZoAAAAJ&hl=en'>google scholar page</a>.
years: [2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  <p style="margin-top:50px">
  {% bibliography -f papers -q @*[year={{y}}]* %}
  </p>
{% endfor %}

</div>
