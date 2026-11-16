# dailygratitude

'오늘의 감사(Daily Gratitude)' 앱의 정책 페이지. GitHub Pages로 `https://dailygratitude.uysoft983.kr`(CNAME)에 게시된다.

| 파일 | 내용 |
| --- | --- |
| `privacy.html` | 개인정보처리방침(한국어 본문 + 영어 번역). 앱 설정 › 정책 및 약관이 이 주소를 연다 |
| `privacy-v1.1.html` | 이전 개인정보처리방침(v1.1, 2025-09-10 시행) 보관본 |
| `terms.html` | 이용약관. 앱 설정 › 정책 및 약관이 이 주소를 연다 |
| `app-ads.txt` | AdMob 판매자 선언. AdMob이 확인하는 곳은 Play 개발자 웹사이트(`https://uysoft983.kr`) 루트의 파일이다 |

- `privacy.html`·`terms.html`은 앱 코드(`src/constants/links.ts`)에 주소가 들어가 있어 이름이나 경로를 바꾸면 출시된 앱의 링크가 깨진다.
- 처리방침은 앱이 실제로 하는 일과 같아야 한다. 앱에서 광고·분석 SDK, 권한, 분석 이벤트를 바꾸면 이 페이지와 Play Console 데이터 보안 신고를 함께 고친다.
- 처리방침을 바꿀 때는 이전 본을 `privacy-v<버전>.html`로 남기고, 새 본의 '처리방침의 변경'에 버전·시행일·바뀐 내용을 적는다.
