# GitHub Pages 버전과 서버형 버전 차이

## GitHub Pages 버전

- 외부 고객에게 링크 공유 가능
- UI/UX 및 화면분할 시연 가능
- 브라우저 저장 기반
- 서버 실행 없음

## Node 서버형 버전

- 실제 파일 업로드
- LAN 내 Player 자동 등록
- SSE 실시간 배포
- Player heartbeat
- TCP/HTTP 네트워크 자동체크
- 예약 배포
- 감사로그

실제 학교 내부망 PoC는 Node 서버형 패키지를 서버 PC 또는 VPS에서 실행해야 합니다.
