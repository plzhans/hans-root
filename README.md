# hans-root

plzhans.com 루트 도메인의 정적 웹 리소스를 관리하기 위한 저장소

## 사용 목적

- Google AdSense 루트 도메인 인증

## 배포

- GitHub Actions를 통해 GitHub Pages로 자동 배포
- `public/` 또는 [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml) 변경 시 트리거
- 수동 배포: workflow_dispatch 지원
