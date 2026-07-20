# 대윤 농장 복숭아 판매 홈페이지

GitHub Pages에 배포할 수 있는 정적 Vite 프로젝트입니다.

## 로컬 실행

```bash
npm install
npm run dev
```

## 빌드

```bash
npm run build
```

빌드 결과는 `dist/` 폴더에 생성됩니다.

## GitHub Pages 배포

1. 이 폴더의 파일을 GitHub 저장소 `main` 브랜치에 업로드합니다.
2. 저장소의 **Settings → Pages → Build and deployment**에서 Source를 **GitHub Actions**로 선택합니다.
3. Actions의 `Deploy to GitHub Pages` 작업이 끝나면 Pages 주소로 접속합니다.

> 이 프로젝트는 정적 HTML 버전입니다. 주문 화면은 브라우저에서 작동하지만 주문 데이터가 온라인 관리자 데이터베이스에 저장되지는 않습니다. 실제 주문 접수·관리자 연동은 기존 온라인 홈페이지를 사용하세요.
