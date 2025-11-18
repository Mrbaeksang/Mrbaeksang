# 👋 안녕하세요! 풀스택 개발자 **백상현**입니다.

> "**성능 개선**과 **시스템 안정성**을 중시하며, 문제를 해결하는 Kotlin/Spring Boot 기반 풀스택 개발자"

**AI 상담 어플리케이션 Google Play 출시 · 1,000명 커뮤니티 운영**

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:qortkdgus95@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/Mrbaeksang)

Java/Kotlin 기반 풀스택 개발과 AI 통합에 열정을 가지고 있으며, 실제 서비스 운영 경험을 바탕으로 성장하고 있습니다.

---

## 🚀 주요 프로젝트

### 1. [AI 철학 상담 앱 - 백엔드](https://github.com/Mrbaeksang/ai-counseling-backend) 🆕
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.4-brightgreen?style=flat-square&logo=spring)](https://spring.io/)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.9.25-7F52FF?style=flat-square&logo=kotlin)](https://kotlinlang.org/)
[![Spring AI](https://img.shields.io/badge/Spring%20AI-1.0.0--M6-13aa52?style=flat-square)](https://spring.io/projects/spring-ai)
[![Tests](https://img.shields.io/badge/Tests-20%2B-blue?style=flat-square)](https://github.com/Mrbaeksang/ai-counseling-backend)

**Kotlin/Spring Boot 기반 AI 철학 상담 서비스**
- 🔗 **플레이스토어**: [마인드톡](https://play.google.com/store/apps/details?id=com.mindtalk.app)
- 💻 **GitHub**: [ai-counseling-backend](https://github.com/Mrbaeksang/ai-counseling-backend)
- 📚 **문서**: [SRS](https://github.com/Mrbaeksang/ai-counseling-backend/blob/main/docs/SRS.md) · [Architecture](https://github.com/Mrbaeksang/ai-counseling-backend/blob/main/docs/system-architecture.md) · [ERD](https://github.com/Mrbaeksang/ai-counseling-backend/blob/main/docs/erd-diagram.md) · [API Spec](https://github.com/Mrbaeksang/ai-counseling-backend/blob/main/docs/api-specification.yaml)

**핵심 성취:**
- **구글 플레이스토어 런칭** (마인드톡 - AI 철학 상담 앱)
- **Spring AI + OpenRouter 통합**: ChatClient를 통한 JSON 스키마 응답 강제 및 fallback 메시지 처리
- **Redis 캐싱 전략**: 캐릭터/세션 페이지, OAuth/Refresh 토큰 TTL 분리로 응답 시간 50% 단축
- **성능 최적화**: 응답 시간 112ms→52ms (53% 단축), 초당 처리량 100→200 req/s (2배 향상)
- **JWT 보안 워크플로**: Google/Kakao OAuth 통합, Refresh 토큰 회전 및 Redis Set 기반 세션 하이재킹 방지
- **메시지 신고 시스템**: 세션 소유 검증 및 중복 차단으로 Play Store 심사 대응

**기술 스택:**
- Runtime: Kotlin 1.9.25 · Spring Boot 3.5.4 · Java 21
- AI: Spring AI ChatClient · OpenRouter API
- Data: Spring Data JPA · Kotlin JDSL · PostgreSQL 15 · Redis
- Auth: JWT · Google/Kakao OAuth
- Quality: ktlint · detekt · JUnit5 · MockK · 20+ 테스트

### 2. [한국 여행 가이드 백엔드](https://github.com/Mrbaeksang/KoreaTravelGuide) 🆕
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.4.1-brightgreen?style=flat-square&logo=spring)](https://spring.io/)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.9.25-7F52FF?style=flat-square&logo=kotlin)](https://kotlinlang.org/)
[![Spring AI](https://img.shields.io/badge/Spring%20AI-1.1.0--M2-13aa52?style=flat-square)](https://spring.io/projects/spring-ai)

**AI 기반 한국 여행 맞춤 가이드 서비스**
- 🔗 **라이브 서비스**: [KoreaTravelGuide](https://korea-travel-guide.vercel.app/)
- 💻 **GitHub**: [KoreaTravelGuide](https://github.com/Mrbaeksang/KoreaTravelGuide)
- 👥 **협업**: 프로그래머스 데브코스 5명 팀 프로젝트

**핵심 성취:**
- **기술 리딩**: Spring AI ChatMemory SQL 스키마 이슈 해결, Jackson Kotlin 버그 패치, ktlint 도입으로 팀 코드 품질 향상
- **AI + 공공 데이터 통합**: OpenRouter API, 한국관광공사 Tour API, 기상청 Weather API 실시간 연동
- **삼중 OAuth 인증**: Google/Kakao/Naver 소셜 로그인 + 역할 기반 접근 제어(RBAC)
- **실시간 채팅**: WebSocket(STOMP) 기반 게스트-가이드 1:1 매칭 시스템
- **성능 최적화**: Redis 캐싱으로 외부 API 응답 시간 단축

**기술 스택:**
- Runtime: Kotlin 1.9.25 · Spring Boot 3.4.1 · Java 21
- AI: Spring AI 1.1.0-M2 · OpenRouter · JDBC ChatMemory
- Data: Spring Data JPA · PostgreSQL · Redis
- Auth: JWT · Google/Kakao/Naver OAuth
- Messaging: WebSocket · STOMP
- Quality: ktlint · SpringDoc OpenAPI · Actuator

### 3. [개발자 커뮤니티 플랫폼](https://devcom.kr) 📌
[![Next.js](https://img.shields.io/badge/Next.js-15.4.4-black?style=flat-square&logo=next.js)](https://nextjs.org)
[![React](https://img.shields.io/badge/React-19.1.0-61DAFB?style=flat-square&logo=react)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?style=flat-square&logo=typescript)](https://www.typescriptlang.org)

**실제 운영 중인 개발자 커뮤니티 서비스**
- 🔗 **라이브 서비스**: [devcom.kr](https://devcom.kr)
- 👥 **운영 현황**: 회원 1,000명
- 💻 **GitHub**: [developers_community](https://github.com/Mrbaeksang/developers_community)

**주요 특징:**
- **AI Q&A 시스템**: OpenRouter 통합으로 자동 코딩 답변 생성
- **이중 콘텐츠 구조**: 메인 사이트(승인제) + 커뮤니티(즉시 게시)
- **엔터프라이즈 아키텍처**: RBAC 권한 관리, Redis 캐싱

### 4. [DevMatch - AI 개발팀 매칭 플랫폼](https://nbe-6-8-2-team08-vaug.vercel.app)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5-brightgreen)](https://spring.io/)
[![Next.js](https://img.shields.io/badge/Next.js-15.4-black)](https://nextjs.org/)

**프로그래머스 데브코스 팀 프로젝트**
- 🔗 **라이브 서비스**: [DevMatch](https://nbe-6-8-2-team08-vaug.vercel.app)
- 💻 **GitHub**: [NBE6-8-2-Team08](https://github.com/Mrbaeksang/NBE6-8-2-Team08)

**담당 역할:**
- Frontend 전체 개발 (Next.js 15, TypeScript)
- OAuth 2.0 소셜 로그인 구현
- Analysis 도메인 개발

---

## 🤝 오픈소스 기여 & 공익 활동

### 5. [Korea Stock Analyzer - MCP Server](https://github.com/modelcontextprotocol/servers) 🏆

**Anthropic MCP 공식 서버 등재 (Python)**
- 📍 [MCP Servers Registry](https://github.com/modelcontextprotocol/servers) 정식 등재
- 🎯 한국 주식 시장 데이터 분석 서버 (Claude AI 통합)
- 🌏 전 세계 개발자들이 한국 주식 시장 데이터 활용 가능

### 6. [Markdown Converter Korean](https://github.com/Mrbaeksang/md-converter-korean)

**한국어 마크다운 변환 도구 (TypeScript)**
- 한글 특수문자 처리 및 한국어 포맷팅 최적화
- 한국 개발자들의 문서 작성 편의성 향상

### 7. [My Site Template](https://github.com/Mrbaeksang/my-site-template)

**Next.js + TypeScript 웹사이트 스타터 템플릿**
- 빠른 프로젝트 시작을 위한 보일러플레이트
- 한국어 주석과 가이드 포함

---

## 🛠️ 기술 스택

### Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=Next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Database & Cache
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### DevOps & Deploy
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)

### Tools & Testing
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![IntelliJ](https://img.shields.io/badge/IntelliJ-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)

### Collaboration
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)

### AI & Auth
![OpenAI](https://img.shields.io/badge/OpenRouter_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![OAuth](https://img.shields.io/badge/OAuth_2.0-4285F4?style=for-the-badge&logo=google&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Mrbaeksang&show_icons=true&theme=radical&include_all_commits=true&count_private=true)

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=qortkdgus95)](https://solved.ac/qortkdgus95/)

</div>

---

## 🏆 주요 성과

- 🌏 **Anthropic MCP 공식 서버 등재** - Korea Stock Analyzer
- 📱 **Google Play 앱 출시** - AI 철학 상담 앱 (마인드톡)
- 👥 **개발자 커뮤니티 운영** - 회원 1,000명
- ⭐ **My Site Template** - Next.js 스타터 템플릿 (GitHub 86 Stars)
- 🎓 **프로그래머스 데브코스** - Java/Kotlin/Spring 백엔드 과정 수료

---

## 📫 Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:qortkdgus95@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mrbaeksang)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/baek.__.sang/)

</div>

---

<div align="center">
  
### 💡 Today's Focus

> "백엔드 개발과 AI 통합으로 실제 가치를 만들어내는 개발자가 되겠습니다."

</div>
