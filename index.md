---
title: Home
layout: home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

Code Complete 2 완독 스터디
{: .fs-9 }

보다 읽기 쉽고 유지 보수성 높은 코드 작성을 위한 실무적 개발 원칙들에 대해 공부합니다.
{: .fs-6 .fw-300 }


---

## 스터디원들

아래는 스터디에 참여한 그룹원들입니다.

#### Contributors

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"></a>
  </li>
{% endfor %}
</ul>

---

## 컨텐츠 목록

1부. 기초 확립
1. 소프트웨어 구현으로의 초대
2. 소프트웨어 개발의 이해를 돕기 위한 비유
3. 준비는 철저하게, 선행 조건
4. 구현 시 결정해야 할 핵심 사항

2부. 고품질 코드 작성
5. 구현 설계
6. 클래스 다루기
8. 방어적 프로그래밍
9. 의사코드 프로그래밍 프로세스

3부. 변수
10. 변수 사용 시 고려할 사항
11. 변수 이름의 기능
12. 기본 데이터형
13. 특이한 데이터형

4부. 명령문
14. 순차적 코드 구성하기
15. 조건문 사용
16. 반복문 제어
17. 특이한 제어 구조
19. 제어와 관련된 일반적인 이슈

5부. 코드 향상
20. 소프트웨어 품질
21. 협력 구현
22. 개발자 테스트
24. 리팩토링
25. 코드 튜닝 전략

6부. 시스템 고려 사항

7부. 소프트웨어 장인 정신

---
[Jekyll]: https://jekyllrb.com
[Markdown]: https://daringfireball.net/projects/markdown/
[Liquid]: https://github.com/Shopify/liquid/wiki
[Front matter]: https://jekyllrb.com/docs/front-matter/
[Jekyll configuration]: https://jekyllrb.com/docs/configuration/
[source file for this page]: https://github.com/just-the-docs/just-the-docs/blob/main/index.md
[Just the Docs Template]: https://just-the-docs.github.io/just-the-docs-template/
[Just the Docs]: https://just-the-docs.com
[Just the Docs repo]: https://github.com/just-the-docs/just-the-docs
[Just the Docs README]: https://github.com/just-the-docs/just-the-docs/blob/main/README.md
[GitHub Pages]: https://pages.github.com/
[Template README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use the template]: https://github.com/just-the-docs/just-the-docs-template/generate
