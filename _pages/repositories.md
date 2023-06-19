---
layout: page
permalink: /repositories/
title: repositories
description: Find replication files for all publications here.
nav: true
nav_order: 3
---

Life-course Differences in Occupational Mobility between Vocationall and Generally Trained Workers in Germany (2023) Viktor Decker, Thijs Bol, Hanno Kruse.
[Replication file](https://github.com/viktor-decker/occupational-mobility).
  
  
  
  
## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
