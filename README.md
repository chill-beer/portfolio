# 정준혁 (Jun) · Frontend Engineer

8년차 프론트엔드 엔지니어입니다. 100만+ 다운로드 리워드 슈퍼앱 **마이비**의 Flutter 앱과 인앱 웹, 광고 플랫폼 **마이비 애드체인**의 **React·TypeScript** 웹을 만들어 왔습니다. 이전에는 블록체인·Web3 도메인에서 지갑·dApp 프론트엔드를 담당했습니다.

🔗 **포트폴리오 사이트**: https://chill-beer.github.io/portfolio/

---

## 핵심 역량

- **웹 프론트엔드 (주력)** — React 18, TypeScript, Next.js, styled-components, React Router, axios
- **모바일 (Flutter · React Native)** — 장기간 단독 리드하며 경험적으로 해결해 온 영역. Flutter/Dart, React Native, BLoC·Cubit, go_router, Firebase
- **연동 · 배포** — OAuth 2.0/JWT, 광고 SDK 연동, S3·CloudFront, App Store·Play, 멀티 환경 빌드

## 프로젝트 (역할·기술 중심 정리)

실제 업무는 회사 비공개 저장소로 진행되어, 도메인과 역할 중심으로 일반화했습니다. 두 개의 프로덕트 라인에 걸쳐 **총 41개 저장소에 기여**했습니다.

### 리워드 광고 플랫폼 (Product Line A)
- **마이비 애드체인 (MyB AdChain)** — 콘텐츠(퀴즈) 중심 보상형 애드네트워크. 제휴 매체별 맞춤 허브·캠페인 이벤트 웹, Daily·캐러셀 UI 개발 (DAU당 일 참여 10.6회 / 광고매출 240원 / 네이티브 전환 30~60%). 서비스 매체: K뱅크·엠넷플러스·데일리샷·똑닥·트레져러·해피스크린·포토위젯·채티·레진코믹스
- **마이비 애드체인 운영 대시보드 (Fully AI 개발)** — 매체·매출·정산·실시간 지표 운영 대시보드. 기획부터 구현·배포까지 전 과정을 AI로 개발. 13개+ 분석 화면, Google OAuth·JWT, S3·CloudFront (React/TS)

### 마이비 (MyB) — 리워드 슈퍼앱 · 대표 서비스
> 📲 **100만+ 다운로드 · 4.8★ (리뷰 2.1만+)** · [Google Play](https://play.google.com/store/apps/details?id=im.myb.android&hl=ko) · [App Store](https://apps.apple.com/kr/app/id6476365625)

퀴즈·만보기·게임·쇼핑·설문·포인트 적금·현금인출을 담은 올인원 앱테크.
- **Flutter 모바일 앱** — Clean Architecture, BLoC→Cubit 전환, 멀티 플레이버 빌드/스토어 배포
- **안정성·시작 성능** — Android 비정상 종료율 약 80%↓ (출시 초기 최고 3%대 → 0.62%), 콜드 스타트 지연 약 70%↓ (최고 약 18% → 5.4%)
- **인앱 웹서비스 다수** — 쇼핑 적립·가입/멤버십·퀴즈/미션·게임/이벤트·배너/프로모션 등 기능 단위 React/TS 웹

## 이전 경력 — FIG (피르마이노베이션그룹) · 2021.08 ~ 2024.08

블록체인 메인넷과 dApp, 서비스 웹의 프론트엔드를 담당했습니다.

- **피르마체인 · Firma Station** ([Google Play](https://play.google.com/store/apps/details?id=com.firma_station_mobile&hl=ko) · [App Store](https://apps.apple.com/kr/app/firma-station/id1611660902)) — 퍼블릭 메인넷 모바일 지갑 앱(스테이킹·거버넌스), 테스트넷 Faucet, VestingAccount용 Genesis Convert 도구, IBC 데이터 시각화·분석 웹, BWB NFT 갤러리, 랜딩 (React/TS, React Native, Apollo GraphQL, Ledger, Chain SDK)
- **BSU (Baby Shark Universe)** — 이더리움 기반 NFT·토큰 서비스 허브. NFT·토큰 에어드랍, ERC20 토크노믹스 관리 웹, 스마트 컨트랙트 배포·관리·테스트 툴 (React/TS, Immutable X·이더리움, MetaMask, ERC20)
- **도뉴 (DONUE)** ([donue.co.kr](https://donue.co.kr/)) — 전자계약 SaaS 랜딩 및 피르마체인 기반 계약서 위·변조 검증 도구 (React/TS, Gatsby, 피르마체인 검증, crypto-js)

## 성과 (Impact)

- **대규모 트래픽 대응 (마이비 애드체인)** — 빠른 출시를 위해 최적화 없이 런칭된 오퍼월을, 매체 규모 확장에 맞춰 단계적으로 최적화(첫 적용 앱 DAU 약 1만 → 똑닥 약 10만 1차 최적화 → 최대 고객 케이뱅크 앱 DAU 약 100만·오퍼월 평균 DAU 약 30만 상정). 첫 진입 통신량 약 80%↓(29→6건) — React Query 캐싱·중복 제거 + IntersectionObserver lazy-load + 스켈레톤을 kill-switch 기반 점진 적용. 서버 최적화 병행으로 처리 한계 2~3천 → 5천 RPS(DB 피크 50%↓)로 확대. 부하 테스트용 유저 시나리오·엔드포인트 가중치 매트릭스 직접 작성.
- **앱 안정성·시작 성능 (마이비)** — 외주로 급히 런칭된 초기 앱을 인하우스 체제로 전환하며 안정화. Android 사용자 인지 비정상 종료율 약 80%↓ (출시 초기 최고 3%대 → 0.62%), 콜드 스타트 지연 발생률 약 70%↓ (최고 약 18% → 5.4%), 동종 앱 중앙값 수준 안착. (Play Console)

## 작업 방식
- 수십 개 독립 저장소를 기능 단위로 오너십을 갖고 설계·배포
- 레거시 → Clean Architecture 점진적 리팩토링
- 디자인 토큰·공통 컴포넌트로 제품 간 UI 일관성 확보
- 복잡한 지표를 읽기 쉬운 차트/카드로 시각화

## 연락
- ✉️ juno87@icloud.com
- 🐙 [github.com/chill-beer](https://github.com/chill-beer)

<!-- 이름·소개·연락처는 자유롭게 수정하세요. 포트폴리오 사이트 URL은 레포 이름/Pages 설정에 맞춰 바꾸면 됩니다. -->
