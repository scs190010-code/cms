# QuickSchool CMS GitHub Pages Hosting Package

QuickSchool CMS 데모를 GitHub Pages에 바로 올릴 수 있는 정적 호스팅 패키지입니다.

## 구조

```text
site/index.html
.github/workflows/deploy-pages.yml
.nojekyll
README.md
docs/GITHUB_PAGES_DEPLOY.md
docs/SERVER_VERSION_NOTE.md
```

## GitHub Pages에서 동작하는 기능

- 콘텐츠 등록 데모
- 이미지/영상/HTML/TXT 파일 브라우저 업로드
- 화면 분할 구성
- Player 화면 반영
- 긴급 송출
- 블랙아웃/복구
- 브라우저 수준 네트워크 체크
- localStorage 저장

## 제한

GitHub Pages는 정적 사이트 호스팅이므로 Node 서버, 실제 서버 업로드, TCP 포트 체크, SSE 서버, Player heartbeat는 실행되지 않습니다. 해당 기능은 Node 서버형 QuickSchool 패키지를 별도 서버/VPS에서 실행해야 합니다.
