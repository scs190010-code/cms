# GitHub Pages 배포 방법

1. GitHub에서 새 Repository를 만듭니다. 예: `quickschool-demo`
2. 이 패키지 전체를 Repository 루트에 업로드합니다.
3. Repository의 Settings → Pages로 이동합니다.
4. Build and deployment의 Source를 `GitHub Actions`로 설정합니다.
5. main 브랜치에 push하면 `.github/workflows/deploy-pages.yml`이 실행됩니다.
6. 배포 완료 후 보통 아래 주소로 접속합니다.

```text
https://사용자명.github.io/저장소명/
```

예:

```text
https://shim-sangwon.github.io/quickschool-demo/
```

## 실패 시 확인

- Settings → Pages → Source가 GitHub Actions인지 확인
- Actions 권한이 활성화되어 있는지 확인
- `site/index.html` 파일이 있는지 확인
- 브라우저 캐시 또는 localStorage 초기화
