---
layout: page
permalink: /repositories/
title: repositories
description: Find replication files for my publications here.
nav: true
nav_order: 4
---

Decker, Viktor, Thijs Bol, and Hanno Kruse. 2023. ‘Life-Course Differences in Occupational Mobility Between Vocationally and Generally Trained Workers in Germany’. Sociological Science 10:857–79
[Replication file](https://github.com/viktor-decker/occupational-mobility).
  
  
  
  
## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
