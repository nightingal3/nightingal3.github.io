---
layout: page
permalink: /publications/
title: Publications
description: Publications by Emmy Liu on language models, reasoning, hallucination, model training, natural language processing, and cognitive science.
years: [2026, 2025, 2024, 2023, 2022, 2021, 2020, 2019]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[website_section=main,year={{y}}] %}
  {% bibliography -f papers -q @*[website_section=workshop,year={{y}}] %}
  {% bibliography -f papers -q @*[website_section=preprint,year={{y}}] %}
  {% bibliography -f papers -q @*[website_section=other,year={{y}}] %}
{% endfor %}

</div>
