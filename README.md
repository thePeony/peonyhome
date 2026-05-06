# 매일피오니 홈페이지

매일피오니를 포트폴리오 쇼케이스가 아니라, 흐려진 작업의 방향을 판단하고 혼재된 상태를 실행 가능한 구조로 재정리하는 사람으로 소개하는 정적 랜딩 페이지입니다.

## 구성

- `index.html`: 단일 페이지 랜딩 본문, SEO 메타, 접근성 구조, 이메일 CTA
- `styles.css`: 색상 토큰, 반응형 레이아웃, 카드/버튼/헤더 스타일
- `favicon.svg`: 매일피오니용 SVG 파비콘
- `site.webmanifest`: 브라우저/PWA 기본 메타
- `vercel.json`: Vercel 정적 배포와 헤더 설정

## 로컬 미리보기

```bash
npm run dev
```

브라우저에서 `http://localhost:4173`을 엽니다.

## Vercel 배포

Vercel에서 이 저장소를 Import한 뒤 별도 빌드 명령 없이 루트 디렉터리를 정적 사이트로 배포하면 됩니다.
