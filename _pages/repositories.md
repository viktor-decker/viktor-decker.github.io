---
layout: page
permalink: /repositories/
title: repositories
description:
nav: false
nav_order: 4
---

**Find replication files for my publications here.**

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
