# 회사·직무별 포트폴리오 틀

`_` 로 시작하는 폴더라 GitHub Pages(Jekyll) 빌드 시 사이트에 게시되지 않습니다.

## 새 페이지 만드는 방법

1. 이 폴더의 `index.html`을 `/<주소>/index.html`로 복사합니다. 예: `/hunau-pm/index.html`
2. `<title>`의 `{{회사 · 직무}}`를 바꿉니다.
3. `[회사별 수정]` 주석이 붙은 구역(HERO, STRENGTHS, PROJECTS)만 수정합니다.
4. 디자인은 `assets/site.css` 한 곳에서 관리하므로 페이지 안에 `<style>`을 추가하지 않습니다.
5. 프로젝트 상세(`projects/`), 이미지(`images/`), 이력서·경력기술서는 복사하지 않고 공용으로 링크합니다.

## 지켜야 할 것

- `<meta name="robots" content="noindex, nofollow">`는 지우지 않습니다. 검색 노출만 막고, 주소를 아는 사람은 볼 수 있습니다.
- `robots.txt`에 회사 페이지 주소를 적지 않습니다. 누구나 열람할 수 있어 지원처 목록이 드러납니다.
- 기간·수치·회사명 등 사실은 메인 `index.html`·`career.html`과 동일하게 유지합니다. 회사별로 바꾸는 것은 강조 순서와 표현뿐입니다.

## 주소 규칙: `<회사>-<직무>`

| 지원 건 | 주소 |
|---|---|
| 현대오토에버 IT PM (CRM 시스템) | `hunau-pm` |
| 카카오페이 프로젝트매니저 | `kapay-pm` |
| 토스 AI 직무 | `toss-ai` |
| SK하이닉스 기술사무직 신입 | `skhy-new` |
| 네이버(+계열사) / 카카오(+계열사) / SK AX | `ne-<직무>` / `ka-<직무>` / `skax-<직무>` |
