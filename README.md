<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=2&height=200&text=Song%20Jinu&fontSize=58&fontColor=ffffff&fontAlignY=35&desc=AI%20Native%20%7C%20Full-Stack%20Engineer&descSize=18&descColor=E8EEFF&descAlignY=68" width="100%"/>

<div align="center">

<br/>

<sup><b>L L M &nbsp;·&nbsp; R A G &nbsp;·&nbsp; A G E N T &nbsp;·&nbsp; H A R N E S S &nbsp; E N G I N E E R I N G</b></sup>

<br/>

🎓 성결대학교 컴퓨터공학과

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Blanc617)
[![Velog](https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=velog&logoColor=white)](https://velog.io/@blanc99/posts)
![Email](https://img.shields.io/badge/jinusong14@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)

<br/>

<img src="https://komarev.com/ghpvc/?username=Blanc617&style=flat-square&color=7A8FBF&label=Profile+Views"/>

</div>

---

---

## 🙋 About Me

> *AI 개발부터 풀스택 서비스까지 직접 구현하는 개발자*

- **AI Native Engineering** — LLM, RAG/Hybrid RAG, Agent, Harness Engineering
- **Full-Stack** — React / TypeScript / Spring Boot / FastAPI
- **Mobile** — React Native (Expo)
- 성결대학교 컴퓨터공학과 (학점 3.87/4.5, 2026.08 졸업예정)
- Seoul, South Korea

---

## 🛠️ Tech Stack

**AI**

![Transformer](https://img.shields.io/badge/Transformer-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Embeddings](https://img.shields.io/badge/Embeddings-412991?style=for-the-badge&logo=openai&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

**Agent / RAG**

![RAG](https://img.shields.io/badge/RAG-0B7285?style=for-the-badge&logo=googlescholar&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-brown?style=for-the-badge&logo=zustand&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)

**Database & Infra**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## Projects

### 📝 [CoverFit](https://github.com/Afraid-Not/cover-letter) — 채용공고 맞춤형 AI 자기소개서 작성 플랫폼
![](https://img.shields.io/badge/AI-412991?style=flat) ![](https://img.shields.io/badge/2026.04_~_2026.05-aaa?style=flat) ![](https://img.shields.io/badge/3인_팀-aaa?style=flat) [![GitHub](https://img.shields.io/badge/View_Repo-0D1117?style=flat&logo=github&logoColor=white)](https://github.com/Afraid-Not/cover-letter)

> 합격 자소서 데이터셋을 RAG로 검색하고, 9명의 AI 평가관이 실시간으로 서류 통과 가능성을 평가하는 자기소개서 작성 SaaS

- 합격 자소서 39건을 **Parent-Child Chunking**으로 임베딩하고 Supabase pgvector 검색을 적용해 질문·채용공고와 유사한 사례를 생성 프롬프트에 주입
- 채용공고 텍스트/스크린샷 분석과 OpenAI + Tavily + DART 기반 **회사 정보 조사**로 직무·기업 맞춤 자소서 생성
- HR·현업·채용 리더 관점의 **9명 LLM-as-a-Judge 평가관**을 병렬 실행하고 **SSE 스트리밍**으로 통과 확률과 피드백을 실시간 제공
- 이력서 업로드·파싱, 글자수 자동 준수, 피드백 기반 재생성, 프로젝트 버전 관리까지 자소서 작성 흐름 구현

**Stack:** `FastAPI` `Python` `Next.js` `React` `TypeScript` `Supabase pgvector` `OpenAI API` `Claude API` `Toss Payments`

---
### 🏪 [BOSS](https://github.com/Neurack4/Boss-2) — AI 기반 소상공인 업무 자동화 플랫폼
![](https://img.shields.io/badge/AI-412991?style=flat) ![](https://img.shields.io/badge/2026.04_~_2026.05-aaa?style=flat) ![](https://img.shields.io/badge/3인_팀-aaa?style=flat) [![GitHub](https://img.shields.io/badge/View_Repo-0D1117?style=flat&logo=github&logoColor=white)](https://github.com/Neurack4/Boss-2)

> 소상공인의 채용·마케팅·매출·문서 업무를 AI 에이전트가 대화형으로 처리하는 통합 플랫폼

- SNS 콘텐츠 작성 → GPT-4o 초안 생성 → 검토 → 플랫폼 자동 업로드 **HITL 파이프라인** 구축, 네이버 블로그는 **Playwright** 자동화 적용
- Instagram·YouTube API 응답을 정규화하고 GPT-4o 기반 **인사이트·액션 아이템 자동 생성**으로 플랫폼 간 성과 비교 문제 해결
- 사용자 프롬프팅을 통한 자동 스케줄링 관리

**Stack:** `FastAPI` `Python` `Next.js` `React` `TypeScript` `Supabase` `Celery` `Redis` `OpenAI API`

---

### ⚽ [Kick Data](https://github.com/Blanc617/kleague_data) — K리그 데이터 분석 플랫폼
![](https://img.shields.io/badge/AI-412991?style=flat) ![](https://img.shields.io/badge/2026.03_~_2026.04-aaa?style=flat) ![](https://img.shields.io/badge/개인_프로젝트-aaa?style=flat) [![GitHub](https://img.shields.io/badge/View_Repo-0D1117?style=flat&logo=github&logoColor=white)](https://github.com/Blanc617/kleague_data)

> K리그 공식·FotMob·Transfermarkt 등 5개 소스에서 실시간 데이터를 수집·분석하는 RAG 기반 플랫폼

- `requests` + `BeautifulSoup`으로 5개 소스 데이터 수집 파이프라인 구축
- 고유명사는 키워드 검색, 맥락·의미는 벡터 검색의 강점을 결합한 **Hybrid RAG** 설계 (BM25 + pgvector)
- RAG 검색·LLM 생성 지연 해결을 위해 **SSE 스트리밍**으로 실시간 출력
- GPT 할루시네이션 방지를 위해 질문 유형 분류 후 수치 쿼리는 **JSON 직접 집계**로 라우팅해 정확도 보장

**Stack:** `FastAPI` `Python` `React 19` `TypeScript` `Vite` `LangChain (LCEL)` `GPT-4o-mini` `Supabase pgvector` `Redis` `Docker` `Render`

---

### 🎯 [NextEnter](https://github.com/Blanc617/NextEnter) — AI 기반 구인구직 플랫폼
![](https://img.shields.io/badge/AI-412991?style=flat) ![](https://img.shields.io/badge/2026.01_~_2026.02-aaa?style=flat) ![](https://img.shields.io/badge/5인_팀-aaa?style=flat) ![](https://img.shields.io/badge/팀장-6B7280?style=flat) [![GitHub](https://img.shields.io/badge/View_Repo-0D1117?style=flat&logo=github&logoColor=white)](https://github.com/Blanc617/NextEnter)

> AI가 이력서를 분석하고 면접을 진행하는 채용 플랫폼

- 한국어 특화 **S-BERT 모델** + 기술 키워드 매칭을 결합한 하이브리드 알고리즘으로 이력서-공고 간 적합도를 **S/A/B/C/F 5단계** 산출
- OpenAI API 실패 시 Gemini API로, LLM 분석 실패 시 규칙 기반 정규식으로 단계적 전환하는 **폴백 구조**로 AI 응답 안정성 확보
- 면접 답변을 **STARR 5개 요소**로 점수화하고 6단계 반응 타입으로 분류해 면접관 피드백 및 최종 합격·불합격 리포트 자동 생성

**Stack:** `Spring Boot 3` `Java 21` `React 19` `TypeScript` `FastAPI` `Python` `MySQL`

---

### 🐶 댕슐랭 — 강아지 품종 분류 및 레시피 AI 서비스
![](https://img.shields.io/badge/AI-412991?style=flat) ![](https://img.shields.io/badge/2026.03-aaa?style=flat) ![](https://img.shields.io/badge/5인_팀-aaa?style=flat) ![](https://img.shields.io/badge/팀장-6B7280?style=flat)

> 사진 한 장으로 견종을 분석하고 맞춤 식단 레시피를 추천하는 AI 앱

- FastAPI 백엔드와 AI 서버를 분리하고 **MobileNetV2 기반 견종 분류 모델** 연동해 견종 분석 기능 구현
- MobileNetV2 파인튜닝 + 단일 전처리·병렬 추론 적용으로 **분석 속도 및 서버 효율 개선**
- Supabase에 품종·유전질환·영양소·식재료·레시피 데이터를 **관계형으로 설계**해 견종별 맞춤 추천 정확도 향상
- GPT-4o-mini를 **RAG** 방식으로 활용하고 Lazy Loading·SSE 캐싱으로 응답 대기시간 및 API 비용 절감

**Stack:** `FastAPI` `Python` `React Native (Expo)` `TypeScript` `Supabase (PostgreSQL)` `GPT-4o-mini`

---

### 🛒 [On & Home](https://github.com/Blanc617/OnAndHome) — 전자제품 E-Commerce 플랫폼
![](https://img.shields.io/badge/FULLSTACK-2563EB?style=flat) ![](https://img.shields.io/badge/2025.11_~_2025.12-aaa?style=flat) ![](https://img.shields.io/badge/5인_팀-aaa?style=flat) ![](https://img.shields.io/badge/팀장-6B7280?style=flat) [![GitHub](https://img.shields.io/badge/View_Repo-0D1117?style=flat&logo=github&logoColor=white)](https://github.com/Blanc617/OnAndHome)

> 구매자와 운영자를 위한 이중 인터페이스 커머스 플랫폼

- React + Spring Boot 기반 쇼핑몰/관리자 백오피스를 **분리 구축**해 사용자·운영자 흐름 독립 관리
- JWT 인증 + OAuth 로그인 연동으로 세션 의존도를 줄이고 **토큰 갱신 구조**로 보안 강화
- 장바구니·주문·결제·재고 차감 흐름을 **JPA 트랜잭션** 기반으로 구현해 데이터 정합성 확보
- **WebSocket 기반 실시간 알림** + DB 알림 이력으로 주문·Q&A·리뷰 이벤트 즉시 전달

**Stack:** `FastAPI` `Spring Boot` `Java` `React` `MySQL` `Tailwind CSS`

---

## 🏆 Awards

| 수상 | 내용 | 날짜 |
|------|------|------|
| 🥇 **대상** | 성결대학교 창의적 공학설계 경진대회 — 학생 커뮤니티 앱 (시간표·학식·전자출결) | 2022.12 |
| 🥈 **우수상** | 성결대학교 창의·창업 경진대회 — 택시 동승 매칭 앱 기획 | 2023.05 |
| 🥈 **우수상** | 성결대학교 전공종합설계 경진대회 — 택시 동승 앱 구현 + **특허 이전** | 2023.12 |

## 📜 Certifications

| 자격증 | 발급기관 | 취득일 |
|--------|----------|--------|
| **SQLD** SQL 개발자 | 한국데이터베이스진흥센터 | 2025.05 |
| **ADsP** 데이터분석준전문가 | 한국데이터베이스진흥원 | 2023.11 |
| **리눅스마스터 2급** | 한국정보통신인력개발센터 | 2026.01 |
| **MOS Master** | Microsoft | 2026.03 |

---

## 🎓 Education & Training

**학력**

| 기간 | 학교 / 전공 | 비고 |
|------|-------------|------|
| 2020.03 ~ 2026.08 | 성결대학교 컴퓨터공학과 | 학점 3.87/4.5 · 졸업예정 |

**교육활동**

| 기간 | 과정 | 내용 |
|------|------|------|
| 2026.03 ~ 2026.05 | 생성형 AI를 활용한 프로젝트 집중 과정 — 하이미디어 | FastAPI · Next.js · Supabase 등 AI 기반 서비스 설계 및 구현 |
| 2025.08 ~ 2026.02 | 생성형 AI를 활용한 JAVA 풀스택 — 하이미디어 | Java · Spring Boot · React · AI API 연동 등 풀스택 전 과정 |
| 2024.06 ~ 2024.11 | 백엔드 개발 실무 교육 (JAVA 백엔드) — 메가스터디 IT 아카데미 | Java · Spring Framework · MySQL 기반 REST API 설계 및 백엔드 실무 |

---

## 🤝 Activities

| 기간 | 활동 | 내용 |
|------|------|------|
| 2024.03 ~ 2025.12 | AI Paper Study | AI 논문 리뷰 동아리 개설 및 회장으로 운영 · 최신 AI 논문 스터디와 리뷰 세션 주도 |
| 2022.03 ~ 2024.08 | 성결대학교 홍보대사 | 성결대학교 공식 홍보대사 · 대외활동팀 **팀장** |

---

## 📚 AI Paper Reviews

| 논문 | 주제 | 리뷰 PDF |
|------|------|----------|
| 준비 중 | AI 논문 리뷰 | PDF 추가 예정 |

---

## 📬 Contact

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Blanc617-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Blanc617)
[![Velog](https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=velog&logoColor=white)](https://velog.io/@blanc99/posts)
[![Email](https://img.shields.io/badge/jinusong14@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jinusong14@gmail.com)

</div>

---

<div align="center">
  <i>"실제로 작동하는 것을 만드는 것이 가장 좋은 공부다"</i>
</div>

