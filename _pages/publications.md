---
layout: page
permalink: /publications/
title: publications
description:
years: [2023]
nav: true
nav_order: 1
---

Decker, Viktor, Thijs Bol, and Hanno Kruse. 2023. ‘[Life-Course Differences in Occupational Mobility Between Vocationally and Generally Trained Workers in Germany](https://sociologicalscience.com/articles-v10-30-857/)’. Sociological Science 10:857–79. 
https://doi.org/10.15195/v10.a30.

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
