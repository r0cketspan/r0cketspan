# 👋 AI Service Developer

> **AI 기능을 실제 서비스로 만들어 운영까지 책임지는 개발자입니다.**<br>
> 음성인식(STT)으로 시작해, 지금은 **LLM · RAG · 에이전트를 기존 시스템에 붙여 현장에서 돌아가는 솔루션**을 만듭니다.<br>
> 공공기관 콜센터에 다국어 실시간 STT를 구축·납품했고, 폐쇄망 환경의 설계부터 운영까지 직접 맡아 왔습니다.

[![Email](https://img.shields.io/badge/Email-choi.debugs.y@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:choi.debugs.y@gmail.com)
<!-- TODO: 블로그·LinkedIn이 있으면 뱃지 1~2개 추가 -->

---

## 💡 What I Do

| 영역 | 하는 일 |
|:--|:--|
| 🤖 **LLM · 에이전트 서비스** | LangGraph 기반 답변·검증 에이전트, MCP 툴 서버, 프롬프트 캐싱·비용 통제 |
| 🔎 **RAG · 지식 구축** | 정형 조회 + Graph RAG 하이브리드 검색, 상담 기록 → 지식 자동 축적 |
| 🛡️ **AI 품질 · 보안** | 골든셋 평가, 매일 자동 채점 + 사람 승인(HITL), 탈옥·프롬프트 인젝션·개인정보 방어 |
| 🎙️ **음성 AI** | 8개 언어 실시간 STT, 언어 판별(LID), 화자 구분, STT/TTS 연동 |
| ⚙️ **서비스 · 인프라** | AI API 게이트웨이, 관리자 시스템, Docker 배포, 폐쇄망 서버 구축·운영 |

---

## 🚀 Featured Projects

### [nadri](https://github.com/r0cketspan/nadri) — 공공데이터 근거로 답하는 관광 챗봇 · `설계 완료, 구현 중`
- **근거 있는 답변**: 관광 사실은 LLM 기억이 아니라 TourAPI 조회 결과로만 답하고, 출처·기준일 표시
- **하이브리드 검색**: 수치·조건 질문은 정형 DB, 서술형 질문은 LLM Wiki + LightRAG(Graph RAG) + 리랭커
- **에이전트 구조**: LangGraph 답변 에이전트 ⇄ 검증 에이전트(툴 결과와 대조, 최대 2회 재작성), 자체 MCP 툴 서버
- **운영 관점**: 변경분만 재수집하는 현행화 배치, 매일 품질 평가 → 개선안 → 관리자 승인(HITL), 여러 겹의 AI 보안
- `Next.js` `FastAPI` `LangGraph` `LangChain` `MCP` `LightRAG` `PostgreSQL+pgvector` `Docker Compose`

### [debugs-choi-harnes](https://github.com/r0cketspan/debugs-choi-harnes) — 스펙 주도 개발 하네스 (Claude Code 플러그인)
- "OOO 만들어줘" 한 문장을 요구사항 → 아키텍처 → 작업 분해 → 스펙/테스트 → 구현까지 **사람 승인 게이트 5개**로 진행
- AI 코딩 도구를 쓰되 **되돌리기 어려운 결정은 사람이 승인**하도록 만든 개발 프로세스. nadri가 이 하네스로 개발 중

---

## 🏭 Work Experience (2024.08 ~)

| | 프로젝트 | 기간 | 맡은 일 |
|:--:|:--|:--|:--|
| 🟢 | **한국관광공사 STT 개선사업** | 진행 중 | LID 도메인 파인튜닝, VAD 튜닝, 화자별 나이·성별 추정, STT → RAG 지식 환류 배치 |
| 🟢 | **1330 상담시스템 유지보수** | 2026.06 ~ | 음성인식·통계분석 시스템 2선 기술지원 |
| ✅ | **한국관광공사 AI 콜인프라 교체** | 2026.09 ~ 2026.11 | AI API 게이트웨이(키 관리·LLM 라우팅), 녹취관리 시스템 개발·납품 |
| ✅ | **한국관광공사 1330 관광안내콜센터** | 2025.08 ~ 2026.02 | 8개 언어 실시간 STT 구축·운영 (LID · 화자 구분 · 후처리) |
| ✅ | **외교부 영사콜센터** | 2025.08 ~ 2025.12 | 한/영 실시간 STT 구축·운영 |

<!-- TODO: 공개 가능한 수치가 있으면 '맡은 일' 끝에 1개씩 (예: LID 정확도 xx% → yy%, 처리 지연 x초 → y초) -->

---

## 🛠️ Tech Stack

| 분야 | 스택 |
|:--|:--|
| **LLM · Agent** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square) ![Ollama](https://img.shields.io/badge/Ollama_(Gemma3)-000000?style=flat-square&logo=ollama&logoColor=white) |
| **RAG** | ![LightRAG](https://img.shields.io/badge/LightRAG-6A1B9A?style=flat-square) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Reranker](https://img.shields.io/badge/bge--reranker-FFD21E?style=flat-square&logo=huggingface&logoColor=black) |
| **Speech AI** | ![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square) ![ECAPA-TDNN](https://img.shields.io/badge/ECAPA--TDNN-FF6F00?style=flat-square) ![Silero VAD](https://img.shields.io/badge/Silero_VAD-2E7D32?style=flat-square) ![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white) |
| **ML** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![CTranslate2](https://img.shields.io/badge/CTranslate2-1F6FEB?style=flat-square) |
| **Backend · Frontend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) |
| **Data · Infra** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) |
| **AI Dev Tools** | ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white) |

---

![snake gif](https://github.com/r0cketspan/r0cketspan/blob/output/github-contribution-grid-snake.svg)
