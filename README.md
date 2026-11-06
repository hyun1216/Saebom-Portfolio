<p align="center">
  <img src="https://raw.githubusercontent.com/hyun1216/Saebom-Portfolio/main/assets/terminal.svg" width="100%" alt="Saebom Portfolio Terminal" />
</p>

## 💻 개인 프로젝트

### 🎁 01. 뭐사주지? mwasajuji | (Kakao Gift Curator)
**카카오톡 선물하기 링크 분석 및 맥락 기반 선물 큐레이션 웹**

`Next.js` · `TypeScript` · `Tailwind CSS` · `Python (Flask)` · `Vercel`

- 🔗 **Links**: [Repository](https://github.com/hyun1216/mwasajuji) ｜ [Live Demo](https://www.mwasajuji.kr/)
- **Key Implementations**:
  - **URL 메타데이터 파이프라인**: 카카오톡 선물하기 공유 링크에서 고유 ID 역추적 및 상품 정보 추출
  - **맥락 매핑 큐레이션**: 선물 가격대 및 상황 키워드 매핑을 통한 최적의 맞춤형 대체 선물 추천
  - **모바일 UX**: 모바일 카카오톡 인앱 브라우저 및 스마트폰 해상도에 최적화된 반응형 뷰포트 구성

<br/>

### 📈 02. 월 배당금 목표 원금 계산기 (Dividend Simulator)
**금융 데이터 API 연동 실시간 현금 흐름 & 절세 복리 시뮬레이터**

`TypeScript` · `Next.js` · `Financial APIs` · `Tailwind CSS` · `Vercel`

- 🔗 **Links**: [Repository](https://github.com/hyun1216/dividend-backend) ｜ [Live Demo](https://mydividend.co.kr/)
- **Key Implementations**:
  - **실시간 데이터 동기화**: 금융 API 기반 주식/ETF 실시간 배당률 및 배당 지급 주기 연동
  - **12개월 현금 흐름 캘린더**: 월·분기·반기 등 상이한 배당 주기를 연중 월별 현금 흐름으로 가공
  - **세후 수령액 & 목표 배당금 계산**: 배당소득세(15.4%) 차감 후 실수령액 계산 및 월별 목표 배당금 산출 로직 구현
  - **경량 서버리스 아키텍처**: 클라이언트 연산 최적화와 Vercel 배포로 빠른 로딩 속도 확보

<br/>

### 🛍️ 03. 내돈내산 저장소 (Honest Review Archive)
**100% 실구매 경험 기록 및 모바일 최적화 미디어 갤러리를 갖춘 프라이빗 리뷰 웹**

`React (Vite)` · `Vanilla CSS` · `Lucide React` · `Vercel`

- 🔗 **Links**: 🔒 Private Repository ｜ [Live Demo](https://my-money-repo.netlify.app/)
- **Key Implementations**:
  - **모바일 퍼스트 반응형 뷰포트**: 스마트폰 브라우징 환경에 맞춘 파스텔 톤 미니멀 카드 UI 및 쾌적한 가독성 설계
  - **실시간 다중 필터 & 검색 엔진**: 제목 및 본문 키워드 실시간 탐색과 다중 카테고리(생활, 전자기기, 다이소 등) 분류 필터 구현
  - **인터랙티브 미디어 갤러리**: 모바일 터치 가로 스와이프 이미지 갤러리, 비디오 임베딩, 외부 구매 링크 메타 카드 컴포넌트 자체 개발
  - **경량 프론트엔드 아키텍처**: Vite 기반의 가벼운 번들링과 순수 CSS(CSS Modules)를 활용해 외부 UI 라이브러리 의존성을 최소화하고 렌더링 성능 최적화
    
<br/>

### 🤖 04. Bottos (US Equity Automated Trading System)
**토스증권 API 연동 미국 정규장 단타·단기 스윙 자동매매 및 리스크 통제 시스템**

`Python` · `Toss Securities API` · `Financial Automation` · `Risk Management`

- 🔒 Private Repository
- **Key Implementations**:
  - **실시간 정규장 모니터링 & 주문 파이프라인**: 토스증권 API 기반 미국 주식 시세 트래킹 및 사전 정의된 단타/스윙 전략 기반 자동 주문 집행
  - **동적 자본 보호 및 킬 스위치(Kill-Switch)**:
    - 초기 한정 시드(20만 원) 기준 동적 포지션 사이징(손실 발생 시 잔여 시드로 자동 축소 재산정)
    - 손실 임계치 도달 시 추가 주문을 원천 차단하는 하드웨어 수준의 안전 정지(Safety Halt) 구현
  - **화이트리스트/블랙리스트 자산 격리 아키텍처**:
    - 장기 투자 및 배당 보유 종목(QLD, SGOV 등)에 대한 스캔·주문·매도 간섭을 코드 레벨에서 원천 배제하는 엄격한 자산 분리 가드 구축
  - **예외 처리 & 내결함성**: 장중 네트워크 지연, API 호출 제한(Rate Limit), 비정상 체결 응답에 대응하는 롤백 및 에러 핸들링
<br/>

### 🏛️ 05. YouthCheck (청년체크)
**광고성 정보와 행정 용어를 배제한 2030 직장인·청년 맞춤형 복지 정책 큐레이션 & 커리어 어시스턴트 플랫폼**

`Next.js` · `TypeScript` · `Tailwind CSS` · `Zustand` · `LocalStorage` · `Mobile-First UI`

- 🔗 **Links**: [Repository](https://github.com/hyun1216/YouthCheck)
- **Key Implementations**:
  - **직관적 자격·혜택 역발상 UI/UX 아키텍처**:
    - 난해한 공공 행정 명칭 대신 `[대상 자격 1줄]`과 `[실제 수령 혜택]`을 카드 전면에 내세우는 역발상 정보 구조 설계
    - 결정적 배제 조건(기초수급, 무소득, 연령 제한 등)을 시각적 하이라이트 배지로 노출해 불필요한 탐색 비용 및 낚시성 정보 이탈 원천 차단
  - **투 트랙(Two-Track) 온보딩 & 조건 필터링 엔진**:
    - 첫 진입 시 '3초 맞춤 온보딩(나이·연봉·고용형태·지역)'과 '전체 둘러보기' 분기 흐름 구현
    - Zustand 기반 전역 상태 관리 및 LocalStorage 영속화를 결합하여 재방문 시 사용자 조건 자동 복원 및 원클릭 상세 필터(FilterBar) 동기화
  - **이력서 & 커리어 연계 기능 확장 (직무능력은행 통합)**:
    - 정책 탐색을 넘어 고용노동부 'NCS 직무능력은행(NCS 계좌제)' 데이터를 연계하여 과거 4대보험 이력, 자격증, 국비 훈련 내역을 한눈에 조회·정리하는 취업 치트키 탭 구축
  - **모바일 퍼스트 반응형 설계 & 노이즈 프리 렌더링**:
    - 이동 환경에 최적화된 반응형 레이아웃 및 터치 친화적 아코디언 컴포넌트를 통해 필요 서류와 공식 신청 다이렉트 링크만 깔끔하게 노출
   

<br/>


### 🖍️ 06. Hangeul_zip (집에서한글)
**유아/초등 부모를 위한 엄마표 한글 파닉스 학습지 및 모바일 맞춤형 부모 해설지 제공 웹 플랫폼**

`Next.js 14 (App Router)` · `Tailwind CSS` · `Supabase` · `Vercel`

- 🔗 **Links**: [Repository](https://github.com/hyun1216/Hangeul_zip.git) ｜ [Live Demo]진행중
- **Key Implementations**:
  - **모바일 최적화 부모 해설지 뷰어**: 부모가 스마트폰을 곁에 두고 아이를 직접 가르칠 수 있도록, 별도 다운로드 없이 화면에 꽉 차게 렌더링되는 모바일 맞춤형 해설지 모달(Modal) 컴포넌트 개발
  - **수준별 커리큘럼 로드맵 & 큐레이션**: '해-달-별-우주' 4단계 테마를 적용해 발달 수준에 맞춘 탭 네비게이션을 구현하고, 'ㄱ(그)+ㅏ(아)=가' 파닉스 기반 학습지 PDF 매핑 기능 구축
  - **사용자 친화적 따뜻한 UI/UX 설계**: 네온과 강한 대비를 배제하고 눈이 편안한 크림 옐로우(Cream Yellow) 중심의 파스텔톤 컬러 팔레트와 곡선(Rounded) 레이아웃을 적용해 유아 교육 서비스 특유의 안정감 제공
  - **BaaS 기반 인증 & 구독 확장성 아키텍처**: Supabase Auth 및 Storage를 활용한 간편 로그인/학습지 관리 시스템 구축, 추후 월 구독형 정기결제(빌링키) 확장을 대비한 유저 결제 상태 및 다운로드 이력 DB 스키마 설계
    
<br/>


### 🎈 07. 소원하늘 (SowonSky)
전 세계 사람들의 소원을 밤하늘 풍선으로 띄우고 교감하는 12시간 시한부 인터랙티브 웹 플랫폼  
Next.js (App Router) · Tailwind CSS · Framer Motion · Supabase Realtime · Vercel
- 🔗 Links: [GitHub Repository](https://github.com/hyun1216/SowonSky) ｜ [Live Demo](https://sowonsky.vercel.app/)
- Key Implementations:
  - **인터랙티브 글로벌 뷰 전환 (Map to Sky):** `react-simple-maps` 기반의 다크 테마 평면 세계 지도에서 특정 국가 선택 시 해당 국가의 밤하늘 캔버스로 자연스럽게 전환되는 줌인 트랜지션 연출
  - **12시간 라이프사이클 & 파티클 모션:** `created_at` 기준 12시간 만료 시 Framer Motion을 통해 풍선이 팽창 후 별가루 파티클로 '펑!' 터지며 사라지는 시한부 수명 시스템 및 실시간 타이머 구현
  - **Supabase 실시간 연동 (Realtime):** WebSocket 채널 구독을 통해 다른 사용자가 띄운 소원 풍선이 새로고침 없이 화면 하단에서 실시간으로 둥실 떠오르는 인터랙션과 응원(❤️) 카운트 동기화
  - **무로그인 어뷰징 방어 & 위치 고정 파이프라인:** Vercel IP 헤더(`x-vercel-ip-country`)를 활용한 접속 지역 자동 판별, SHA-256 IP 해싱 기반 1일 2회 작성 제한, 다국어 및 극단적 유해 키워드 2중 정규식 필터링 적용
 
<br/>


---

### 📦 Previous Work & Background
- **Enterprise RPA Experience**: 과거 엔터프라이즈 환경에서 레거시 ERP, 세무 회계 솔루션 연동 및 비즈니스 프로세스 자동화를 전담했던 기록입니다.  
  👉 [RPA 실무 아카이브 둘러보기 (Repository)](https://github.com/hyun1216/RPA-Portfolio)

<br/>

---

## 🛠 Tech Stack

### Frontend & Web
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Automation & Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=for-the-badge&logo=power-automate&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

<br/>

---

## 📬 Contact

<a href="https://github.com/hyun1216">
  <img src="https://img.shields.io/badge/GitHub-hyun1216-181717?style=flat-square&logo=github"/>
</a>
<a href="mailto:your_email@example.com">
  <img src="
