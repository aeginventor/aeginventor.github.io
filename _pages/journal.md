---
layout: archive
title: "Journal"
permalink: /journal/
author_profile: true
---

Development journal, reflections, and milestones.
과정, 생각, 경험과 이정표를 기록합니다.

{% include base_path %}

{% assign category_name = "Journal" %}
{% assign category_posts = site.categories[category_name] %}

{% if category_posts and category_posts.size > 0 %}
  {% for post in category_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  아직 Journal에 등록된 글이 없습니다.
{% endif %}
