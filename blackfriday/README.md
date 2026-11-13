# YC 블랙프라이데이 2026 랜딩 (식스샵 주입)

- 원본: 넥스트우드 블프 랜딩(nextwood.co.kr/nextwood-blackfriday) — 제품·가격·기간 동일, 로고·문구만 YC코퍼레이션
- 실행 주소: https://ycgroup.co.kr/yc-blackfriday (스크립트 TARGET_PATH)
- 미리보기: https://yc-mkt.github.io/landing-yc/blackfriday/
- 식스샵 연결(헤더 또는 바디 코드에 한 줄):
  `<!-- YC 블랙프라이데이 2026 / 마케팅 --><script src="https://yc-mkt.github.io/landing-yc/blackfriday/yc-blackfriday.js?v=20261113-01" defer></script>`
- 수정 시 파일 고치고 `?v=` 숫자 올리기
- 상담 폼: 원본과 같은 Cloudflare Worker로 전송 — Worker 허용 출처에 https://ycgroup.co.kr 추가 필요
