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

<h2>Main Conferences &amp; Journals</h2>
{%- for y in page.years %}
  {% bibliography -f papers -q @*[website_section=main,year={{y}}] %}
{% endfor %}

<h2>Workshop Papers</h2>
{%- for y in page.years %}
  {% bibliography -f papers -q @*[website_section=workshop,year={{y}}] %}
{% endfor %}

<h2>Preprints</h2>
{%- for y in page.years %}
  {% bibliography -f papers -q @*[website_section=preprint,year={{y}}] %}
{% endfor %}

<h2>Other</h2>
{%- for y in page.years %}
  {% bibliography -f papers -q @*[website_section=other,year={{y}}] %}
{% endfor %}

</div>
