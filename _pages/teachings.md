---
layout: page
title: teaching
permalink: /teachings/
description: 
nav: true
---

<p indent="2em">
  I love teaching because every class feels like a shared journey—we’re discovering ideas together, and my students’ questions constantly renew my own curiosity. I strive to create a warm, inclusive atmosphere where learning is not just about answers but about exploration. For me, being in the classroom is more than teaching—it’s a meaningful practice that opens the door to what Heidegger calls “authentic experience”: a way of engaging where we connect deeply with ideas, with one another, and with ourselves as learners; or in his words, "the stance in which we at bottom are able to own up to ourselves."
  <!-- (Basic Problems of Phenomenology, p. 160) -->
  
  <br>
  Below is a list of the current and some of my previous courses:
  <br>
</p>

<!-- pages/teachings.md -->
<div class="teachings-list">
  {%- assign sorted_teachings = site.teachings | sort: "date" | reverse -%}
  {%- assign teachings_by_year = sorted_teachings | group_by_exp: "t", "t.date | date: '%Y'" -%}
  {%- for year in teachings_by_year %}
  <h2 class="category">{{ year.name }}</h2>
  <div class="table-responsive">
    <table class="table table-sm table-borderless">
      {%- for teaching in year.items %}
      <tr>
        <th scope="row">{{ teaching.date | date: "%B" }}</th>
        <td>
          <a class="teaching-title" href="{{ teaching.url | relative_url }}">{{ teaching.title }}</a>
          <span class="text-muted">&mdash; {{ teaching.description }}</span>
        </td>
      </tr>
      {%- endfor %}
    </table>
  </div>
  {%- endfor %}
</div>
