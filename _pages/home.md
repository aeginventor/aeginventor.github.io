---
layout: archive
permalink: /
title: ""
author_profile: true
---

## 배우고, 만들고, 기록합니다

안녕하세요. **Memoization Library**에 오신 것을 환영합니다.

이곳은 개발 공부와 프로젝트 경험을 기록하는 개인 기술 블로그입니다.

새롭게 이해한 개념, 문제를 해결한 과정, 프로젝트를 진행하며 내린 선택과 회고를 남깁니다.

컴퓨터 과학에서 메모이제이션은 이미 계산한 결과를 저장해두었다가 필요할 때 다시 사용하는 기법입니다.

이 블로그도 제가 배우고 경험한 것을 저장하고, 미래의 제가 다시 꺼내 활용할 수 있는 공간으로 만들어가려고 합니다.

## 이곳에 기록하는 것

### [Journal](/journal/)

과정과 생각, 경험과 이정표를 기록합니다.

### [Notes](/notes/)

개발 공부 중 새롭게 배운 내용을 기록합니다.

### [Solutions](/solutions/)

오류와 문제를 분석하고 해결한 과정을 기록합니다.

### [Projects](/projects/)

프로젝트의 목표, 설계, 구현 과정과 회고를 남깁니다.

## Latest Posts

{% include base_path %}

{% for post in site.posts limit:5 %}
  {% include archive-single.html %}
{% endfor %}
