---
layout: page
permalink: /resumes/
title: resumes
description: resumes by categories in reversed chronological order, labeled by field. 
years: [2021, 2022]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
