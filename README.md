# 팔레트키친

1인 가구를 위한 레시피북 서비스 "팔레트키친"의 사전 신청 랜딩 페이지입니다.

- `index.html` 한 파일로 된 정적 페이지예요. 빌드 과정이 없어요.
- 방문·클릭·신청 기록은 Google Apps Script 엔드포인트로 보내요(`index.html` 안 `ENDPOINT`).

## Netlify 배포

GitHub 저장소를 연결하고 Build command는 비워 두고, Publish directory는 `/`(루트)로 두면 돼요.
사이트 주소가 `palette-kitchen.netlify.app`이 아니면 `index.html`의 `og:url`, `og:image` 주소를 실제 주소로 바꿔 주세요.
