# STRUCTURE · mimoboosim-sample (v0.2.1 · 옅은 핑크 그라데이션 + 마젠타 레터링 · 모서리 2px · 배포 예정 mimoboosim-sample.lgt3232.workers.dev)

```
mimoboosim-sample/
├─ index.html                     단일 파일 (CSS · JS 인라인)
├─ wrangler.toml                  name = mimoboosim-sample
├─ .assetsignore                  img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ mm-cormorant.woff2 · mm-cormorant-i.woff2   영문 라벨 · 카드 제목 (Cormorant Garamond 400–600 정체 · 이탤릭, 영문만)
├─ mm-pretendard.woff2            본문 · 한글 (Pretendard 300–700, 페이지 글자 전부)
├─ mm-logo.svg                    간판 붓글씨 벡터 로고 (헤더 · 히어로 · 푸터)
├─ mm-hero.webp                   히어로 매장 입구
├─ mm-front.webp                  소개 안내데스크
├─ mm-wax.webp · mm-lash.webp     가격 카드(왁싱 · 속눈썹)
├─ mm-lycon.webp                  교육 LYCON 인증 스티커
├─ favicon.png · og-mm.jpg
├─ img/                           다올 제공 원본 105장 + _원문.md (배포 제외 · 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(+ 900px 미만 `.snav`) → 히어로(핑크 그라데이션 + 번짐) → `#about`(그라데이션) → `#price` 가격 카드 5(#FFF9FA · 사진 카드 먼저) → `#academy` 교육(그라데이션) → `#booking` 예약 안내(진한 분홍 그라데이션 띠 · 마젠타 제목) → `#visit`(#FFF9FA · 구글 지도) → 푸터(그라데이션) + 모바일 `.quick`.

## 버튼 · 링크
- 전화 `tel:050713680878`(메인, 네이버 번호): 헤더 · 히어로 · 예약 안내 · 오시는 길 · 푸터 · 하단 바
- 문자 `sms:01075960878`: 히어로 · 예약 안내 · 하단 바
- 수강문의 `tel:01075960878`: 교육
- 인스타 `https://www.instagram.com/_mimoboosim_/`: 히어로 · 교육 · 푸터 · 하단 바
- 네이버 길찾기 `map.naver.com/p/entry/place/1764735148` · 네이버 플레이스 · 블로그 · 스마트스토어(푸터)

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 한글은 Pretendard만, Cormorant는 영문 · 숫자만.
