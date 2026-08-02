---
layout: archive
title: "Solutions"
permalink: /solutions/
author_profile: true
---

개발 과정에서 만난 오류와 문제를 분석하고 해결한 과정을 기록합니다.

{% include base_path %}

{% assign category_name = "Solutions" %}
{% assign category_posts = site.categories[category_name] %}

{% if category_posts and category_posts.size > 0 %}
  {% for post in category_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  아직 Solutions에 등록된 글이 없습니다.
{% endif %}
