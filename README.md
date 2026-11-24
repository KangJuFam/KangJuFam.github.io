# kangjufam.github.io

강주놀이터 채널이 쓰는 API 클라이언트 `mac (Minecraft Auto Channel)` 의 공개 안내 페이지.

YouTube API 규정 준수 감사가 **기본 액세스 URL**과 **개인정보처리방침 URL**을
필수로 요구해서 만들었다. 도구 자체는 공개 배포하지 않는다.

| 파일 | 주소 | 쓰이는 곳 |
|---|---|---|
| `index.html` | <https://kangjufam.github.io/> | 감사 양식 "기본 액세스 URL" |
| `privacy.html` | <https://kangjufam.github.io/privacy.html> | 감사 양식 "개인정보처리방침 URL" |
| `games-terms.html` | <https://kangjufam.github.io/games-terms.html> | Play 게임 앱 전부의 「서비스 약관」 링크 (판매자 상태 선언, 2026-11-04) — 위 `terms.html` 은 mac 용이라 따로 둔다. **새 게임을 Play 에 올리면 1장 목록(ko · en)에 더한다** — Play 가 「앱에 구체적으로 적용」을 요구. 앱마다 링크는 `games-terms.html#<패키지 끝 이름>` |
| `mulgil-rush/play/` | <https://kangjufam.github.io/mulgil-rush/play/> | 물길 러시 웹 빌드 — 아이폰 · 브라우저 사람 테스트용(검색 제외 noindex). 빌드 원본은 `kangjufam-app-mulgil-rush` `BuildApk.BuildWeb` → `app/Builds/web` 을 통째로 덮어쓴다 |
| `frog-pond/play/` | <https://kangjufam.github.io/frog-pond/play/> | 테라리움(가칭) 웹 빌드 — 아이폰 · 브라우저 사람 테스트용(검색 제외 noindex). 빌드 원본은 `kangjufam-app-frog-pond` `BuildPlayer.BuildWeb` → `app/Builds/web` 을 통째로 덮어쓴다 |
| `hidden-object/play/` | <https://kangjufam.github.io/hidden-object/play/> | 숨은그림찾기(가칭) 웹 빌드 — 아이폰 · 브라우저 사람 테스트용(검색 제외 noindex). 빌드 원본은 `kangjufam-app-hidden-object` `BuildWeb` → `app/Builds/web` 을 통째로 덮어쓴다 |
| `spot-diff/play/` | <https://kangjufam.github.io/spot-diff/play/> | 틀린그림찾기(가칭) 웹 빌드 — 아이폰 · 브라우저 사람 테스트용(검색 제외 noindex). 빌드 원본은 `kangjufam-app-spot-diff` `BuildWeb` → `app/Builds/web` 을 통째로 덮어쓴다 |
| `bow-rush/play/` | <https://kangjufam.github.io/bow-rush/play/> | 활 러시(가칭) 웹 프로토 — 폰 · 브라우저 사람 테스트용(검색 제외 noindex). 원본은 `kangjufam-app-bow-rush` `prototype/index.html` 한 파일 — 그대로 복사해 덮어쓴다 |
| `lifting-king/play/` | <https://kangjufam.github.io/lifting-king/play/> | 리프팅 왕 웹 빌드 — 토스 판(앱인토스) + 개발 패널 · 폰 · 브라우저 사람 확인용(검색 제외 noindex). 토스 브리지가 없어 순위 판 · 햅틱은 꺼진 모양. 빌드 원본은 `kangjufam-app-lifting-king` `TossBuild.BuildWeb` → `app/Builds/web` 을 통째로 덮어쓴다 |

내용을 고치면 `minecraft-auto-channel/docs/API-AUDIT.md` 의 답안과 어긋나지 않는지
확인할 것. 감사팀은 양쪽을 대조한다.

> 2026-10-04: 세 페이지(index · privacy · terms)의 연락처를 개인 메일에서 `kangjufam@gmail.com` 으로 바꿨다 — 공개물에 실명 · 개인 메일을 두지 않는다. 감사(2026-09-19 승인) 기록은 `minecraft-auto-channel/docs/API-AUDIT.md` 진행 기록. 커밋 작성자는 `KangJuFam` (이 저장소 로컬 git 설정, 2026-10-04 기록 재작성).

> 2026-10-11: 공개 연락처를 `kangjufam.studio@gmail.com` 하나로 — 세 페이지(`kangjufam@gmail.com`)와 앱 방침 4개(`KangJuFam.Tech@gmail.com`) 모두. 사람 결정 「모두 kangjufam.studio 로」(`project-policy/01_프로젝트_진행_원칙.md` 6장). 감사 답안 기록은 `minecraft-auto-channel/docs/API-AUDIT.md` 진행 기록.
