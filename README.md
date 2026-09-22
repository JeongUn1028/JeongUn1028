<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=transparent&fontColor=703ee5&height=120&section=header&text=Lee%20JeongUn&fontSize=70&fontAlignY=30&desc=Frontend%20Developer&descAlignY=70&descAlign=80" />
  <p><b>"문제를 정확히 이해하고, 더 나은 구조와 해결 방법을 고민하는 프론트엔드 개발자 이정운입니다."</b></p>
  <a href="https://www.leejeongun.com" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio%20Site-black?style=for-the-badge&logo=About.me"/>
  </a>
  <a href="https://velog.io/@jeongun1028" target="_blank">
    <img src="https://img.shields.io/badge/Tech%20Blog-black?style=for-the-badge&logo=Velog"/>
  </a>
  <a href="https://github.com/JeongUn1028" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub"/>
  </a>
</div>

<br />

## 🏢 Work Experience

- **헤디** | 프론트엔드 개발자 (2026.09 ~ 재직중)
  - 레이더 기반 로봇을 제작하는 회사의 로봇 매니지먼트 웹 서비스 프론트엔드 개발

- **부산대학교** | 개발자 인턴 (2026.01 ~ 2026.02) · 2개월

- **데이터리** | 개발팀 대리 / 프론트엔드 개발자 (2023.05 ~ 2024.08) · 1년 4개월
  - 국립국어원 수주 사업의 웹 서비스 개발, 배포 및 운영
  - 오픈소스 데이터 라벨링 도구(Doccano)를 사업 요구사항에 맞게 구조 분석 및 커스터마이징 (Vue.js + TypeScript 적용)
  - AWS + Docker 기반의 실제 사용자 서비스 배포 및 운영·유지보수
  - 동시 사용자 증가로 발생한 서비스 지연 문제를 Frontend뿐 아니라 Python Backend 코드까지 추적·분석하여 동시 처리 인원 설정(1→30) 개선으로 병목 해결
  - 데이터 검수 및 후처리 가공 과정을 코드로 동기화/자동화하여 작업 생산성 및 검수 정확도 대폭 향상

<br />

## 🎓 Education & Certifications

- **창원대학교** | 컴퓨터공학과 학사 졸업 (2023.08)
- **정보처리기사** | 과학기술정보통신부 (2025.09)

<br />

## 🛠 Tech Stack

### 💻 Main Skills
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=Next.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=Vue.js&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/>

### 🔧 Tooling & Database & Backend
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=Prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=Supabase&logoColor=white"/>
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=Vitest&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=AmazonAWS&logoColor=white"/>

<br />

## 📂 Projects

### **ReelTrailer** · OTT & 콘텐츠 통합 탐색 풀스택 웹 서비스
[GitHub](https://github.com/JeongUn1028/reeltrailer-next) · [Live](https://reeltrailer.vercel.app/)  
`2026.06 ~ 2026.08`

- **CSR 한계 극복을 위한 Next.js App Router 풀스택 아키텍처 전환** (Prisma 6 + PostgreSQL / Supabase DB)
- **사용자 경험(UX) 최적화**: `Intercepting & Parallel Routes`를 이용한 모달 UX 구축 및 URL 공유/새로고침 시 독립 페이지 제공 딥링크 지원, Suspense 기반 스켈레톤 UI 적용
- **서버리스 DB 커넥션 병목 문제 해결**: Prisma P2024 타임아웃 방지를 위한 병렬 DB 쿼리 순차 실행 리팩토링 및 Supabase Transaction Pooler 적용
- **데이터 파이프라인 자동화**: TMDB/YouTube API 통합 및 Vercel Cron 기반 Route Handler를 구축하여 국내 OTT 라이선스 데이터 매일 자동 동기화
- **품질 지표 개선**: Lighthouse 검사 기준 성능 100점(+9), 접근성 98점(+12), 동적 Metadata/OpenGraph 적용으로 SEO 100점(+8) 달성

### **ItsMe** · 공개 포트폴리오 & 관리자 시스템
[GitHub](https://github.com/JeongUn1028/ItsMe) · [Live](https://www.leejeongun.com/)  
`2026.05 ~ 2026.06`

- Next.js App Router 기반의 **공개 포트폴리오 + Admin 관리자 시스템** 일체형 웹 서비스 구축
- `Intercepting Routes + Parallel Routes` 기반으로 목록 진입 시 URL 모달 UI, 직접 링크 접근 시 독립 상세 페이지 제공
- Serverless 환경 제약을 극복하고자 **Server Actions + GitHub Contents API**를 연동하여 별도 CMS 없이 Markdown 콘텐츠를 관리하고 커밋/자동 배포되는 파이프라인 구축
- `jose` 라이브러리와 `httpOnly Cookie` 기반 JWT 관리자 인증 및 Middleware 라우트 보호 구현

<br />

## 📚 Learning & Study

### **Next.js App Router 학습 프로젝트 (Onebite Books)**
[GitHub](https://github.com/JeongUn1028/App-Router-Onebite-books) · [Live](https://one-bite-books-app-tawny.vercel.app/)  
`2026.03 ~ 2026.04`

- Next.js App Router의 핵심 기능(RSC/RCC 역할 분리, Intercepting Routes 모달, 에러 바운더리) 학습
- Server Actions 기반 리뷰 등록/삭제 및 `revalidateTag`를 통한 변경 영역 정밀 캐시 갱신 구조 경험

<br />

## 🧠 Development Philosophy

> **문제를 정확히 이해하고, 상황에 맞는 기술과 구조를 선택합니다.**

실무에서는 실제 사용자가 이용하는 서비스를 운영하며 발생한 프론트엔드/백엔드 병목 현상을 파악하고 해결했습니다.

개인 및 토이 프로젝트에서는 주어진 제약 사항(서버리스 환경, DB 커넥션 등)을 고려해 적합한 기술 스택(Server Actions, Supabase, Prisma, GitHub API 등)과 라우팅 아키텍처를 직접 설계했습니다.

단순히 최신 기술을 사용하는 것에 그치지 않고, **왜 해당 구조를 선택했는지와 그로 인한 트레이드오프를 명확히 설명할 수 있는 개발**을 지향합니다.
