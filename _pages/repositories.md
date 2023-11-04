---
layout: page
permalink: /repositories/
title: Repositories
description:
nav: true
nav_order: 3
---

You can visit my <a href="https://github.com/alirezafarashah"><ins>Github</ins></a> page to view all the repositories that I have created or contributed to.

## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
