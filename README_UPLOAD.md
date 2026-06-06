# ScopeWorks / ImjangBox v3 refined upload guide

## 포함 파일

- `index.html`
  - 메인 ScopeWorks 홈페이지에 `/imjangbox/` 진입 버튼 추가
  - Header nav에 `ImjangBox` 추가
  - Product 섹션에 `View ImjangBox` 버튼 추가

- `imjangbox/index.html`
  - 기존 ScopeWorks `style-v3.css`를 그대로 사용하는 제품 소개 페이지
  - 주요 헤드라인을 한국어 중심으로 정리
  - Hero, Product, What breaks, Workflow, MVP Status, Scope, Contact 구성 유지

- `sitemap.xml`
  - `/imjangbox/` 포함 상태 유지

## 업로드 방법

1. ZIP 압축을 푼다.
2. GitHub `scopeworks-site` 레포 루트에 들어간다.
3. `index.html`을 루트의 기존 파일과 교체한다.
4. `imjangbox/index.html`을 기존 파일과 교체한다.
5. `sitemap.xml`을 기존 파일과 교체한다.
6. Commit message:
   `Refine ImjangBox page and add homepage entry points`

## 확인할 URL

- https://scope-works.net/
- https://scope-works.net/imjangbox/
- https://scope-works.net/sitemap.xml
