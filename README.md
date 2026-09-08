# 백상현

**핵심 가설을 작은 PoC로 검증하고, 실제 사용과 운영을 통해 제품을 확장하는 풀스택 개발자입니다.**

마드라스체크에서 **OKR 서비스를 단독 개발·출시**했습니다. **[사주박사](https://play.google.com/store/apps/details?id=com.sajubaksa.android)를 Google Play에 출시**했으며, 직접 만든 [baeksang.dev](https://baeksang.dev)를 **월 방문자 약 1만 명** 규모로 운영합니다.

[프로젝트](https://baeksang.dev/work) · [개발 철학](https://baeksang.dev/harness) · [개발 기록](https://baeksang.dev) · [이메일](mailto:qortkdgus95@gmail.com)

## 실무 경험

### 마드라스체크 · 제품 개발과 개발팀 자동화

- **OKR 서비스 단독 개발·출시** — 기획부터 웹·백엔드 개발과 배포까지 담당했습니다.
- **로컬 LLM 에이전트 구현** — 리패턴 구축형 제품에 적용할 자체 호스팅 모델의 업무 도구 실행 흐름을 개발했습니다.
- **QA 대응 자동화** — 저장소에 등록된 QA 이슈를 주기적으로 수집하고 해결 작업을 실행하는 로직을 개발했습니다.

<details>
<summary>구현 내용 보기</summary>

OKR에서는 목표·실행 업무 연결, 진척도 집계와 권한 관리를 구현했습니다. 리패턴에서는 상용 AI 중심의 기존 구성에 자체 호스팅 모델을 사용하는 경로를 마련하고, 업무 도구의 계획·실행·결과 검증·재계획을 구현했습니다. 구축형 제품 적용을 위한 개발입니다.

</details>

## 직접 개발·운영하는 서비스

**[baeksang.dev](https://baeksang.dev) — 월 방문자 약 1만 명의 AI·개발 콘텐츠 서비스**  
Vercel Analytics 기준 방문자 수입니다. 콘텐츠 수집, 중복 제거, LLM 큐레이션과 발행 파이프라인을 직접 개발해 운영합니다. LLM 처리 실패 후 전체 작업을 반복하지 않도록 입력 해시별 체크포인트를 저장하고, 같은 입력의 성공 결과를 재사용해 발행 작업을 재개하도록 구현했습니다. [AI 다이제스트](https://baeksang.dev/daily)

**[사주박사](https://play.google.com/store/apps/details?id=com.sajubaksa.android) — Google Play에 출시한 AI 운세 서비스**  
웹·모바일·백엔드를 개발했습니다. AI 상담과 대화 저장, 크레딧 과금·인앱결제를 연결하고 결제 웹훅 재전송에 대응하는 처리를 구현했습니다.

## 오픈소스 프로젝트

- **[DeepCloak](https://github.com/Mrbaeksang/deepcloak)** — 리서치 엔진과 브라우저를 연결한 Python CLI·MCP 도구. 수집 경로 선택과 근거 기록을 구현했습니다.
- **[My Site Template](https://github.com/Mrbaeksang/my-site-template)** — 화면에서 내용을 편집할 수 있는 Next.js 포트폴리오 템플릿. [활용 강의](https://www.youtube.com/watch?v=U6zL8qittGk)
- **[Korea Stock Analyzer MCP](https://github.com/Mrbaeksang/korea-stock-analyzer-mcp)** — DART 공시와 KRX 시세를 조회·분석하는 Python MCP 서버.

GitHub Stars: **DeepCloak 60 · My Site Template 94 · Korea Stock Analyzer MCP 23** — 2026.09.08 기준

## 기업 의뢰 프로젝트

### AskUp · Upstage AI 대화 앱

**Upstage 의뢰로 크로스플랫폼 앱·AI 대화 백엔드·관리자 화면을 개발했습니다.**

<details>
<summary>대화·문서 처리 구현 보기</summary>

Kotlin Multiplatform 앱에 AI 응답 스트리밍, OCR 문서 처리와 pgvector 기반 대화 기억을 구현했습니다. OAuth 로그인과 토큰 갱신, 대화 저장을 앱과 백엔드에 연결했습니다.

Kotlin · Spring Boot · Spring AI · Kotlin Multiplatform · Next.js · PostgreSQL

</details>

[시연 영상](https://www.youtube.com/watch?v=4j4Pxz3KDT0) · [프로젝트 상세](https://baeksang.dev/work/askup)

### Qnova · 영어 학습자료 생성 서비스

**교재 업로드 → 학습자료 생성 → 편집·미리보기 → PDF·DOCX 출력까지 전체 개발했습니다.** 강사가 생성 결과를 확인하고 수정해 수업 자료로 사용할 수 있는 흐름을 구현했습니다.

[서비스](https://qnova.co.kr)

### Timely AI MCP Hub · 전체 설계·개발

**Timely AI(현 Upstage) 의뢰로, 외부 도구 실행부터 예약 작업과 결과 알림까지 연결한 MCP Hub를 설계·개발하고 소스코드를 전달했습니다.**

<details>
<summary>에이전트와 예약 실행 구현 보기</summary>

외부 API와 업무 도구를 연동하고, 실행 결과에 따라 다음 도구를 호출하는 에이전트 흐름을 구현했습니다. 병렬 도구 실행, 진행 상태 스트리밍, 자연어 예약과 결과 알림을 연결하고 예약 실행 이력과 실패 상태를 기록하도록 구성했습니다.

TypeScript · NestJS · Next.js · BullMQ · PostgreSQL · Redis · MCP

</details>

## 수상 · 평가 · 자격

- **APEX Expert AI 실무역량평가 — 44명 중 3위 · 88/100점**  
  조코딩AX파트너스, 2026.08 파일럿 회차. 실기 **55/60점** · AI 활용 **10/10점**.
- **2025 AI_TOP_100 Finalist**
- **Upstage Solar Agent Partner Program Stage 1 선정**

<details>
<summary>교육 · 자격 · 어학 보기</summary>

- **Anthropic Academy 18종 수료**
- **SQLD** · 한국데이터산업진흥원
- **TOEIC 815점**

</details>

## 주로 사용하는 기술

**AI·백엔드** · MCP, LangGraph, vLLM, Kotlin/Spring Boot, Python/FastAPI, TypeScript/NestJS  
**웹·모바일** · React, Next.js, Kotlin Multiplatform  
**데이터·운영** · PostgreSQL, pgvector, Redis, Docker
