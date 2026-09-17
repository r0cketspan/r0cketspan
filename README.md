# 🎙️ Speech AI Research Engineer

## 🧑‍💻 About Me

> **음성인식(STT) · 언어식별(LID)을 연구개발하는 Speech AI 엔지니어입니다.**<br>
> AI 파운데이션 모델을 도메인 데이터로 파인튜닝하고, LLM과 결합해 **실서비스에 적용되는 음성 AI 솔루션**을 만듭니다.
<a href="https://dev-tier.vercel.app/r0cketspan">
  <img src="./assets/devtier.png" width="480" alt="DevTier Card" />
</a>

[![Email](https://img.shields.io/badge/Email-choi.debugs.y@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:choi.debugs.y@gmail.com)
[![Notion](https://img.shields.io/badge/Notion-Coming_Soon-000000?style=flat-square&logo=notion&logoColor=white)]()


---

## 🔬 Currently Working On

- 🎙️ **다국어 콜센터 STT · LID 연구개발** — 도메인 데이터 기반 모델 파인튜닝으로 인식 정확도와 언어 전환 안정성 개선
- 🤖 **AI 결합 음성 솔루션 개발** — LLM / sLLM을 STT와 결합한 전사 후처리 · 상담 요약 · RAG 지식 구축

---

## 🏭 Projects

| 상태 | 기간 | 프로젝트 | 👤 역할 → 납품 · 적용 |
|:--:|:--|:--|:--|
| ![ONGOING](https://img.shields.io/badge/ONGOING-2EA44F?style=flat-square) | 진행 중 | 🧭 **한국관광공사<br>AI 콜인프라 교체** | **AI Gateway(일부) · 녹취관리자 시스템 개발 → 솔루션 납품**<br>▸ **AI Gateway** — 서비스별 API Key 관리, 호출 시스템에 맞는 Key 주입 → LLM 서비스 라우팅 · 응답 반환<br>▸ **녹취관리자** — 실시간 STT 연계로 콜 종료 시 STT 전사 결과 ↔ 콜 정보 매핑<br>▸ LLM 기반 녹취 요약으로 녹취 내용 관리<br>▸ 실시간 STT 연계 **실시간 청취** 기능 개발 |
| ![ONGOING](https://img.shields.io/badge/ONGOING-2EA44F?style=flat-square) | 진행 중 | 🧭 **한국관광공사<br>STT 개선사업** | **LID · 화자 분석 고도화 + STT 기반 RAG 환류 로직 개발**<br>▸ 도메인 데이터 기반 **LID 모델 파인튜닝**<br>▸ VAD 옵션 튜닝으로 발화 분절 개선<br>▸ VAD 단위 **화자구분 → 화자별 나이 · 성별 추정** 모델 적용<br>▸ **RAG 환류 일배치** — 콜 단위 대표질의 · 대표답변 · 유사질의 LLM 생성 → LLM 품질 평가 → 선별 결과 벡터 임베딩 · 상담 RAG 등록 |
| ![ONGOING](https://img.shields.io/badge/ONGOING-2EA44F?style=flat-square) | 2026.06 ~ | 🔧 **1330 관광통역안내<br>상담시스템 유지보수** | **2선 기술지원**<br>▸ STT · LID · TA(통계 · 분석) 시스템 기술지원 |
| ![DONE](https://img.shields.io/badge/DONE-6E7681?style=flat-square) | 2025.08 ~ 2026.02 | 🧭 **한국관광공사<br>1330 관광안내콜센터** | **8개 언어 실시간 STT 설계 · 구축 · 운영 · 고도화**<br>▸ ECAPA-TDNN + MLP 기반 LID 개발 → 언어별 STT 엔진 자동 라우팅<br>▸ 조사 · 어미 · 기능어 스코어링 2차 언어 검증 로직 적용<br>▸ XLM-RoBERTa 문맥 기반 도메인 용어 교정 적용<br>▸ DMZ 중계 서버 경유 LLM 번역 연동 · 통역 3자 통화 대응 |
| ![DONE](https://img.shields.io/badge/DONE-6E7681?style=flat-square) | 2025.08 ~ 2025.12 | 🇰🇷 **외교부<br>영사콜센터** | **한/영 실시간 STT 설계 · 구축 · 운영**<br>▸ 8kHz 전화망 음성 전처리 · 콜/언어 감지 파이프라인 구성<br>▸ Selvy STT(한) + Faster Whisper(영) 하이브리드 구성<br>▸ Gemma3 기반 전사 후처리 · 키워드 추출 → 사내 KMS 연동<br>▸ WER 기반 STT 품질 검증 체계 수립 |

---

## 🛠️ Tech Stack

| 분야 | 스택 |
|:--|:--|
| **Language** | ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) |
| **Framework** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) |
| **Database** | ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) |
| **OS** | ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMjggMTI4Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBkPSJNNjcuMzI4IDY3LjMzMWg2MC42NjlWMTI4SDY3LjMyOHptLTY3LjMyNSAwaDYwLjY2OVYxMjhILjAwM3pNNjcuMzI4IDBoNjAuNjY5djYwLjY2OUg2Ny4zMjh6TS4wMDMgMGg2MC42Njl2NjAuNjY5SC4wMDN6Ii8+PC9zdmc+Cg==) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white) ![Rocky Linux](https://img.shields.io/badge/Rocky_Linux-10B981?style=for-the-badge&logo=rockylinux&logoColor=white) |
| **Infra** | ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white) ![Docker](https://img.shields.io/badge/Docker_(Dev)-2496ED?style=for-the-badge&logo=docker&logoColor=white) |
| **Monitoring** | ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) |
| **IDE** | ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white) ![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white) |
| **AI Tools** | ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white) |

#### 🧠 AI Foundation

| 영역 | 모델 | 용도 |
|:--|:--|:--|
| 🎙️ **STT** | ![Whisper](https://img.shields.io/badge/Whisper_(FT)-412991?style=for-the-badge) ![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=for-the-badge&logo=elevenlabs&logoColor=white) ![Selvy](https://img.shields.io/badge/Selvy_STT-1A73E8?style=for-the-badge) | 다국어 실시간 음성인식 |
| 🌐 **LID · Speaker** | ![ECAPA](https://img.shields.io/badge/ECAPA--TDNN_(FT)-FF6F00?style=for-the-badge) | 언어식별 · 화자구분 |
| 🔊 **Voice Analysis** | ![Silero](https://img.shields.io/badge/Silero_VAD-2E7D32?style=for-the-badge) ![SpeechLLM](https://img.shields.io/badge/SpeechLLM-9C27B0?style=for-the-badge) | 발화 구간 검출 · 나이/성별 추정 |
| 💬 **NLP · LLM** | ![XLM-R](https://img.shields.io/badge/XLM--RoBERTa_(FT)-FFB300?style=for-the-badge&logoColor=black) ![OpenAI API](https://img.shields.io/badge/OpenAI_API_(GPT)-412991?style=for-the-badge) ![Gemma3](https://img.shields.io/badge/Gemma3_(Ollama)-000000?style=for-the-badge&logo=ollama&logoColor=white) | 도메인 용어 교정 · 번역 · 요약 · QA 생성/평가 |
| ⚙️ **ML Framework** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![SpeechBrain](https://img.shields.io/badge/SpeechBrain-FF6F00?style=for-the-badge) ![CTranslate2](https://img.shields.io/badge/CTranslate2-1F6FEB?style=for-the-badge) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white) | 파인튜닝 · 실시간 추론 |

<details>
<summary>📋 사용 모델 상세 (Checkpoints)</summary>

| Task | Model |
|:--|:--|
| LID | `speechbrain/lang-id-voxlingua107-ecapa` (Fine-tuned) + 언어별 MLP 헤더 |
| STT | `openai/whisper-large-v3-turbo` (Fine-tuned) · ElevenLabs `scribe_v2` · Selvy STT |
| VAD | `snakers4/silero-vad` |
| Speaker Diarization | `speechbrain/spkrec-ecapa-voxceleb` |
| Age / Gender | SpeechLLM-2B |
| Domain Term Correction | XLM-RoBERTa-large |
| Translation | OpenAI `gpt-4o-mini` |
| sLLM | Gemma3 (Ollama) |

</details>

---

![snake gif](https://github.com/r0cketspan/r0cketspan/blob/output/github-contribution-grid-snake.svg)

