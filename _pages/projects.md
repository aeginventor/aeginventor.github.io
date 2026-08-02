---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

프로젝트의 목표, 설계, 구현 과정과 회고를 기록합니다.

{% include base_path %}

{% assign category_name = "Projects" %}
{% assign category_posts = site.categories[category_name] %}

{% if category_posts and category_posts.size > 0 %}
  {% for post in category_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  아직 Projects에 등록된 글이 없습니다.
{% endif %}
