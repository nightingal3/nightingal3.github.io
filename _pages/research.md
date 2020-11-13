---
layout: archive
title: "Research"
permalink: /research/
author_profile: false
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


## Manuscripts in Progress
<strong>Rapid information gain and cross-linguistic ordering preferences in lexical composition (in revision at Cognition) </strong>  
Coauthors: Yang Xu


<strong>Gender Differences in Medical Student End-of-Shift Feedback: A Multicenter, Qualitative Analysis</strong>  
Coauthors: MH Tessler, Roger Levy


<strong>Chaining and the process of scientific innovation (journal version)</strong>  
Coauthors: Yang Xu  


<strong>Metascience project (unofficial name)</strong>  
Coauthors: Joseph Williams

## Journal papers
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Conference papers
{% for post in site.conferences reversed %}
  {% include archive-single.html %}
{% endfor %}

## Posters
{% for post in site.posters reversed %}
  {% include archive-single.html %}
{% endfor %}



