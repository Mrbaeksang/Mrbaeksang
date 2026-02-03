<h1 align="center">백상현 · AI 활용 풀스택 개발자</h1>

<p align="center">
  <a href="https://brianimpact.notion.site/AI_TOP_100-FINALIST-2ed0e052072a80aeadedefff1f2ea6bd">
    <img src="./AI_TOP_100_logo_Finalist_Badge_A.png" alt="AI_TOP_100 2025 Finalist" height="100"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Google%20Play%20출시-2개-34A853?style=for-the-badge&logo=google-play&logoColor=white" alt="Google Play"/>
  <img src="https://img.shields.io/badge/Upstage%20외주%20계약-1건-FF6F00?style=for-the-badge" alt="외주"/>
  <img src="https://img.shields.io/badge/커뮤니티%20운영-1,000명-7C3AED?style=for-the-badge" alt="커뮤니티"/>
</p>

<p align="center">
  <a href="mailto:qortkdgus95@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/Mrbaeksang"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>
  <a href="https://devcom.kr"><img src="https://img.shields.io/badge/devcom.kr-4285F4?style=flat-square&logo=google-chrome&logoColor=white"/></a>
</p>

---

## 🚀 주요 프로젝트

### 1. AskUp — AI 대화 어시스턴트 `Upstage 외주 계약`

[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.7-6DB33F?style=flat-square&logo=spring-boot)](https://spring.io/)
[![Kotlin](https://img.shields.io/badge/Kotlin-2.2.0-7F52FF?style=flat-square&logo=kotlin)](https://kotlinlang.org/)
[![Spring AI](https://img.shields.io/badge/Spring%20AI-1.0.0--M8-13aa52?style=flat-square)](https://spring.io/projects/spring-ai)
[![Tests](https://img.shields.io/badge/Tests-53%2B-blue?style=flat-square)]()

**Upstage와의 외주 계약으로 개발한 AI 대화 서비스** — Backend + KMP Mobile + Admin Dashboard

- 🧠 **Spring AI + SSE 스트리밍** 기반 실시간 AI 응답, 파일 첨부 시 Upstage OCR 자동 처리
- 🗄️ **PgVector 장기 기억** — Mem0 스타일 2단계 파이프라인 (사실 추출 → ADD/UPDATE/DELETE/NONE)
- 📱 **Kotlin Multiplatform** — Android/iOS 단일 코드베이스, Compose Multiplatform UI
- 🔐 Google/Apple OAuth + JWT 토큰 회전, 28개 API 엔드포인트

<details>
<summary>상세 기술 스택</summary>
<br>

| 구분 | 기술 |
|------|------|
| Backend | Spring Boot 3.5.7 · Kotlin 2.2.0 · Java 21 · Spring AI · PostgreSQL + PgVector |
| Mobile | Kotlin 2.3.0 · Compose Multiplatform 1.9.3 · Voyager · Koin · Ktor Client |
| Admin | Next.js 16.1 · TypeScript · shadcn/ui · TanStack Query |
| Auth | OAuth2 Resource Server · Google/Apple ID Token 검증 · JWT |
| Quality | ktlint · JUnit5 · MockK · 53+ 테스트 |

</details>

---

### 2. 사주박사 — AI 운세 서비스 `3플랫폼 출시`

[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.7-6DB33F?style=flat-square&logo=spring-boot)](https://spring.io/)
[![KMP](https://img.shields.io/badge/KMP-Compose%20Multiplatform-7F52FF?style=flat-square&logo=kotlin)](https://kotlinlang.org/)
[![Toss](https://img.shields.io/badge/Toss%20미니앱-0064FF?style=flat-square)](https://minion.toss.im/3tQu0ibn)

**AI 기반 사주·타로·궁합 서비스** — Android + iOS + Toss 미니앱

- 📱 [**Play Store**](https://play.google.com/store/apps/details?id=com.sajubaksa.android) · [**Toss 미니앱**](https://minion.toss.im/3tQu0ibn)
- 🤖 **OpenRouter 멀티모델** — 유동적 모델 선택으로 비용/성능 최적화
- 💰 **수익화 구현** — RevenueCat 인앱결제 + AdMob 리워드 광고 + 크레딧 시스템
- 🔮 9개 도메인 (사주·타로·꿈해몽·궁합·채팅 등), 37+ API 엔드포인트

<details>
<summary>상세 기술 스택</summary>
<br>

| 구분 | 기술 |
|------|------|
| Backend | Spring Boot 3.5.7 · Kotlin · Java 21 · Spring AI · OpenRouter · PostgreSQL |
| Mobile | Kotlin Multiplatform · Compose Multiplatform · Voyager · RevenueCat · AdMob |
| Toss | Next.js 16.1 · React 18 · @apps-in-toss/web-framework · TanStack Query · Zustand |
| Auth | Google/Apple OAuth · JWT · 토큰 회전 |

</details>

---

### 3. [마인드톡 — AI 철학 상담 앱](https://github.com/Mrbaeksang/ai-counseling-backend) `Google Play 출시`

[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.4-6DB33F?style=flat-square&logo=spring-boot)](https://spring.io/)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.9.25-7F52FF?style=flat-square&logo=kotlin)](https://kotlinlang.org/)
[![Tests](https://img.shields.io/badge/Tests-20%2B-blue?style=flat-square)](https://github.com/Mrbaeksang/ai-counseling-backend)

**AI 철학자 캐릭터와 대화하는 상담 서비스** — [Play Store](https://play.google.com/store/apps/details?id=com.mindtalk.app) · [GitHub](https://github.com/Mrbaeksang/ai-counseling-backend) · [API Spec](https://github.com/Mrbaeksang/ai-counseling-backend/blob/main/docs/api-specification.yaml)

- ⚡ **성능 53% 개선** — 응답 시간 112ms → 52ms, 처리량 100 → 200 req/s
- 🗃️ **Redis 캐싱 전략** — 캐릭터/세션/토큰 TTL 분리, 세션 하이재킹 방지
- 🔐 Google/Kakao OAuth + Refresh 토큰 회전
- 📋 Play Store 심사 대응 — 메시지 신고 시스템, 세션 소유 검증

<details>
<summary>상세 기술 스택</summary>
<br>

| 구분 | 기술 |
|------|------|
| Backend | Spring Boot 3.5.4 · Kotlin 1.9.25 · Java 21 · Spring AI · OpenRouter |
| Data | PostgreSQL 15 · Redis · Spring Data JPA · Kotlin JDSL |
| Auth | JWT · Google/Kakao OAuth |
| Quality | ktlint · detekt · JUnit5 · MockK · 20+ 테스트 |

</details>

---

### 4. [devcom.kr — 개발자 커뮤니티](https://devcom.kr) `회원 1,000명 운영`

[![Next.js](https://img.shields.io/badge/Next.js-15.4-000000?style=flat-square&logo=next.js)](https://nextjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?style=flat-square&logo=typescript)](https://www.typescriptlang.org)

**실제 운영 중인 개발자 커뮤니티** — [devcom.kr](https://devcom.kr) · [GitHub](https://github.com/Mrbaeksang/developers_community)

- 👥 **회원 1,000명** 실서비스 운영
- 🤖 AI Q&A 시스템 — OpenRouter 통합 자동 코딩 답변
- 🏗️ 이중 콘텐츠 구조 (승인제 메인 + 즉시 게시 커뮤니티), RBAC 권한 관리

---

### 5. [PollDash — 실시간 투표 커뮤니티](https://polldash.app) `라이브 서비스`

[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.0.1-6DB33F?style=flat-square&logo=spring-boot)](https://spring.io/)
[![Next.js](https://img.shields.io/badge/Next.js-16.1-000000?style=flat-square&logo=next.js)](https://nextjs.org)

**투표 결과를 바 차트 레이스로 시각화하는 커뮤니티** — [polldash.app](https://polldash.app)

- 🏎️ **바 차트 레이스 애니메이션** — Framer Motion 기반 10~30초 순위 변동 시각화
- 🗳️ 8개 카테고리, 시간대별 랭킹, 비공개 투표 (shareToken), 중첩 댓글
- 🔔 Discord 웹훅 에러 알림, Google/Apple OAuth

---

## 🤝 오픈소스

| 프로젝트 | 설명 |
|----------|------|
| [**Korea Stock Analyzer MCP**](https://github.com/modelcontextprotocol/servers) 🏆 | Anthropic MCP 공식 서버 등재 — 한국 주식 시장 데이터 분석 (Python) |
| [**Markdown Converter Korean**](https://github.com/Mrbaeksang/md-converter-korean) | 한국어 마크다운 변환 도구 (TypeScript) |
| [**My Site Template**](https://github.com/Mrbaeksang/my-site-template) ⭐ 86 | Next.js + TypeScript 웹사이트 스타터 템플릿 |

---

## 🛠️ 기술 스택

| 분류 | 기술 |
|------|------|
| **Backend** | Kotlin · Java · Spring Boot · Spring AI · JPA · Kotlin JDSL |
| **Mobile** | Kotlin Multiplatform · Compose Multiplatform |
| **Frontend** | Next.js · React · TypeScript · Tailwind CSS |
| **Database** | PostgreSQL · PgVector · Redis |
| **AI** | OpenRouter · Spring AI · SSE Streaming |
| **DevOps** | Docker · GitHub Actions · Vercel · Railway |
| **Auth** | OAuth 2.0 (Google/Apple/Kakao) · JWT |

---

## 🏆 주요 성과

- 🏆 **2025 AI_TOP_100 FINALIST** — 카카오 · 브라이언임팩트 · 카카오임팩트 주최
- 📋 **Upstage 외주 계약** — AskUp AI 대화 서비스 개발
- 📱 **Google Play 앱 출시 2건** — 마인드톡, 사주박사
- 🌏 **Anthropic MCP 공식 서버 등재** — Korea Stock Analyzer
- 👥 **개발자 커뮤니티 1,000명 운영** — devcom.kr
- ⭐ **My Site Template** — GitHub 86 Stars
- 🎓 **프로그래머스 데브코스** — Java/Kotlin/Spring 백엔드 과정 수료

---

## 📊 GitHub Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Mrbaeksang/Mrbaeksang/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mrbaeksang/Mrbaeksang/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/Mrbaeksang/Mrbaeksang/output/github-snake.svg" />
</picture>

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Mrbaeksang&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true)

</div>

---

<p align="center">
  <a href="mailto:qortkdgus95@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>&nbsp;
  <a href="https://github.com/Mrbaeksang"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>&nbsp;
  <a href="https://devcom.kr"><img src="https://img.shields.io/badge/devcom.kr-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white"/></a>
</p>
