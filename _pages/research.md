---
layout: page
permalink: /research/
title: 연구분야
description: 레이저 진단기법 기반 계측기법을 활용하여 액체추진기관 인젝터의 특성계측 및 설계 개선을 위한 연구를 수행합니다.
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
