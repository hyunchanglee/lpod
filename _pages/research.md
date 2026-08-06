---
layout: page
permalink: /research/
title: 연구분야
description: 레이저 진단기법 기반 분무 계측과 인젝터 성능평가를 중심으로 연구를 수행합니다.
nav: true
nav_order: 1
horizontal: false
---

<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
  </div>
</div>
