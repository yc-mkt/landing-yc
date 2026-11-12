# YC 공통 랜딩페이지

식스샵(ycgroup.co.kr)에 헤더 코드 두 줄로 넣는 랜딩 파일입니다. 절차는 YC DB 프로젝트의 `docs/sixshop-landing-guide.md`.

구조: 페이지마다 폴더 하나
```
<페이지-slug>/
  index.html   미리보기용
  page.css     루트 id 범위로만
  page.js      TARGET_PATH + PAGE_ID 이중 잠금
  img/         웹용 압축 이미지(장당 200~500KB)
```

식스샵 헤더 코드:
```html
<link rel="stylesheet" href="https://yc-mkt.github.io/landing-yc/<페이지-slug>/page.css?v=YYYYMMDD-01">
<script src="https://yc-mkt.github.io/landing-yc/<페이지-slug>/page.js?v=YYYYMMDD-01" defer></script>
```
수정하면 `?v=` 숫자를 올려야 캐시가 갱신됩니다.
