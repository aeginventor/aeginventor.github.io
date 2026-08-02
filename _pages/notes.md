---
layout: archive
title: "Notes"
permalink: /notes/
author_profile: true
---

개발 공부 중 배운 내용을 정리하는 공간입니다.

{% include base_path %}

{% assign category_posts = site.posts | where_exp: "post", "post.categories contains 'Notes'" %}

{% if category_posts.size > 0 %}

  {% for post in category_posts %}
    {% include archive-single.html %}
  {% endfor %}

{% else %}

아직 Notes에 등록된 글이 없습니다.

{% endif %}
