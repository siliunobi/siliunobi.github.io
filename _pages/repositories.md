---
layout: page
permalink: /repositories/
title: service
description: Services to the scientific community.
nav: true
nav_order: 5
---

<h3>Programm Committees</h3>

- 22nd USENIX Symposium on Networked Systems Design and Implementation ([NSDI 2025](https://www.usenix.org/conference/nsdi25))
- 25th International Conference on Formal Engineering Methods ([ICFEM 2024](https://icfem2024.info/))
- 24th International Conference on Formal Engineering Methods ([ICFEM 2023](https://formal-analysis.com/icfem/2023/))

<h3>Reviewing</h3>

- Journals: [The VLDB Journal](https://link.springer.com/journal/778), Journal of Logical and Algebraic Methods in Programming ([JLAMP](https://www.sciencedirect.com/journal/journal-of-logical-and-algebraic-methods-in-programming)), Science of Computer Programming ([SCP](https://www.sciencedirect.com/journal/science-of-computer-programming))


- Conferences: FM, ICFEM, FASE, TASE

<h3>Others</h3>

- Dagstuhl Seminars: Ensuring the Reliability and Robustness of Database Management Systems [21442](https://www.dagstuhl.de/en/seminars/seminar-calendar/seminar-details/21442) (participant)

<!--
{% if site.data.repositories.github_users %}

## GitHub users

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>

---

{% if site.repo_trophies.enabled %}
{% for user in site.data.repositories.github_users %}
{% if site.data.repositories.github_users.size > 1 %}

  <h4>{{ user }}</h4>
  {% endif %}
  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.liquid username=user %}
  </div>

---

{% endfor %}
{% endif %}
{% endif %}

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
-->
