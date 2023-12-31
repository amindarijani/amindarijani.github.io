---
layout: page
permalink: /repositories/
title: repositories
description: You can take a look at my GitHub activity in the blink of an eye.
nav: true
nav_order: 4
---

## GitHub profile

{% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.html username=user %}
  {% endfor %}
</div>

---

{% if site.repo_trophies.enabled %}
{% for user in site.data.repositories.github_users %}
  {% if site.data.repositories.github_users.size > 1 %}
  <h4>{{ user }}</h4>
  {% endif %}
  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.html username=user %}
  </div>

  ---

{% endfor %}
{% endif %}
{% endif %}

## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}

## GitHub Achievements

<div>
  <a href="https://github.com/amindarijani">
    <img src="https://img.shields.io/badge/YOLO-3CAE1D?logo=github&logoColor=white" alt="YOLO Badge">
    <img src="https://img.shields.io/badge/Pull%20shark-2EA9A1?logo=github&logoColor=white" alt="Pull Shark Badge">
    <!-- Add more badges with similar structure -->
  </a>
</div>


<div>
  <a href="https://github.com/amindarijani">
    <img src="https://img.shields.io/github/followers/amindarijani?label=Followers&style=social" alt="Followers Badge">
    <img src="https://img.shields.io/github/stars/amindarijani?label=Stars&style=social" alt="Stars Badge">
    <img src="https://img.shields.io/github/commits-since/amindarijani/latest/main?label=Commits&logo=github" alt="Commits Badge">
    <!-- Add more badges with similar structure -->
  </a>
</div>

