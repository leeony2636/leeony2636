# 하주성

## 🌐 Portfolio

👉 [웹 포트폴리오 바로가기](https://leeony-portfolio.vercel.app/)

> 다양한 현장에서 쌓은 문제 해결 경험을 바탕으로  
> Python과 AI 기술을 실제 프로젝트로 구현하고 기록하고 있습니다.

---

## About Me

Python과 AI·Deep Learning을 공부하며
음성 인식, 머신러닝, LLM Agent를 실제 서비스와 프로젝트로 구현하는 개발자입니다.

다양한 현장 경험을 통해 문제를 발견하고 해결해 온 방식에 익숙하며,
이 경험을 바탕으로 데이터와 AI를 활용한 프로젝트를 개발하고 있습니다.
최근에는 MCP 기반 운영 보조 Agent와 문서 검색을 활용한 RAG 챗봇으로 개발 경험을 확장하고 있습니다.

아이디어를 결과물로 끝내지 않고
실험 → 개선 → 문서화 → 배포까지 이어지는 과정을 중요하게 생각합니다.

## Background

다양한 현장 경험을 통해 문제를 직접 발견하고 해결해 왔으며,
현재는 그 경험을 Python과 AI 기술을 활용한 개발 역량으로 확장하고 있습니다.

---

## Featured Projects

### 🎵 AI Music Genre Classifier

WAV 음악 데이터를 분석하여 **10개 음악 장르를 예측하는 AI 프로젝트**

[GitHub Repository](https://github.com/leeony2636/ai-music-final) · [Live Demo](https://ai-music-final-mj2gmrph3khrrncd5dbsgb.streamlit.app/)

`Python` `PyTorch` `ResNet18` `Librosa` `Scikit-learn` `Streamlit`

**Development**

- RandomForest 기반 기본 장르 예측 모델 구현
- 장르별 신뢰도 시각화
- 여러 WAV 파일 비교 기능 구현
- 예측 이력 기능 추가
- 3초 Segment 기반 Mel-Spectrogram 변환
- ImageNet 사전학습 ResNet18 Fine-tuning
- 데이터 증강 및 하이퍼파라미터 조정
- SpecAugment 적용
- AS-IS / TO-BE 모델 성능 비교
- Epoch별 학습 과정 시각화
- Streamlit 웹 애플리케이션 통합

**Result**

- Validation Accuracy: **76.47% → 82.32%**
- Model Improvement: **+5.85%p**
- Epoch별 Validation Accuracy / Train Loss / Learning Rate 시각화
- 6강 기본 → 7강 고급 → 8강 Deep Learning 구조로 기능 확장
- 3초 구간별 예측을 평균하는 WAV 업로드 기반 음악 장르 예측 웹 구현
- Streamlit 배포 완료

---

### 🤖 GitHub Weekly Three-Model Project Reviewer

GitHub 프로젝트를 **Qwen · Command A · Gemini 세 AI 모델이 독립적으로 분석하고 서로 교차검증하여 주간 리뷰를 자동 생성하는 Multi-AI 프로젝트**

[GitHub Repository](https://github.com/leeony2636/github-weekly-project-reviewer)

`Python` `GitHub Actions` `Qwen` `Command A` `Gemini` `GitHub API` `SQLite`

**Development**

- Qwen / Command A / Gemini 기반 3-Model Review 구조 구현
- 세 모델의 독립적인 1차 프로젝트 분석
- 모델 간 Cross Review 및 Consensus 검증
- 최소 2개 모델이 동의한 항목만 최종 결과로 채택
- 최신 `main.py`와 `README.md`, 최근 7일 변경 메타데이터 중심의 핵심 프로젝트 리뷰
- 실제 Git diff의 변경 파일·라인·코드 근거 검증
- 특정 Pull Request를 대상으로 하는 PR Cross Review
- 무료 API 환경을 고려한 입력 크기 및 모델 호출 제한
- Quota Guard 기반 API 사용량 보호
- 모델별 1차 의견과 교차검증 결과 보존
- GitHub Actions 기반 매주 월요일 오전 9시(KST) 주간 자동 리뷰 구성
- 리뷰 결과를 GitHub Issue로 자동 생성
- JSON / SQLite 기반 실행 기록 저장

**Result**

- Qwen / Command A / Gemini 3개 모델 리뷰 파이프라인 구축
- 독립 분석 → 교차검증 → Consensus 구조 구현
- 프로젝트 핵심 파일 중심의 토큰 절약형 리뷰 방식 적용
- 모델별 의견 / 교차검증 / 최종 종합 결과를 GitHub Issue에서 확인 가능
- GitHub Actions 기반 주간 리뷰와 PR 교차검증 워크플로우 구성
- 검토 범위와 모델 실행 성공·실패 상태를 결과에 함께 기록

---

### 🐳 Docker FastAPI Multi-AI API

FastAPI를 기반으로 **감정분석 · AI 채팅 · 이미지 설명 기능을 하나의 API 서버로 통합한 프로젝트**

[GitHub Repository](https://github.com/leeony2636/docker-fastapi-sentiment-api)

`Python` `FastAPI` `Docker` `Pydantic` `HTTPX` `Hugging Face` `OpenRouter`

**Development**

- FastAPI 기반 REST API 서버 구현
- Hugging Face 기반 텍스트 감정분석 API 구현
- OpenRouter 기반 AI Chat API 추가
- 이미지 업로드 기반 AI Image Description API 추가
- `/predict` · `/chat` · `/describe-image` 엔드포인트 구성
- 기능별 Router 분리를 통한 코드 구조 개선
- 환경변수를 이용한 API Key 및 Token 관리
- Pydantic 기반 요청 데이터 검증과 채팅 입력 길이 제한
- Swagger `/docs` 기반 API 테스트
- Docker 기반 실행 환경 구성

**Result**

- 감정분석 · AI 채팅 · 이미지 분석 3개 기능 통합
- Hugging Face Inference API 연동 완료
- OpenRouter AI 모델 연동 완료
- Swagger 기반 API 테스트와 감정분석 HTTP 200 응답 결과 기록
- 기존 감정분석 API를 Multi-AI API 프로젝트로 확장

---

### 👨‍🍳 ChefEar — AI Voice Cooking Assistant

음성으로 레시피를 검색하고 조리 단계를 진행할 수 있도록 설계한 팀 프로젝트입니다.

[개인 STT 기록 Repository](https://github.com/leeony2636/Chefear-stt)

`Python` `PyTorch` `Whisper` `wav2vec2` `QLoRA` `CTranslate2` `faster-whisper`

**My Role — STT Fine-tuning**

- Whisper Small, wav2vec2, Whisper Large-v3-turbo 비교
- Whisper Large-v3-turbo 기반 QLoRA 파인튜닝
- 요리명·재료명·수량·단위·조리동작 중심의 음성 인식 평가
- Fixed100 / New500 기준 WER·CER 비교
- 숫자·수량·단위 취약유형 분석 및 데이터 보강
- 최종 STT 모델 선정 및 팀 서비스 통합 테스트
- CTranslate2 int8 및 faster-whisper 기반 추론 구조 검증
- STT 개발 과정과 평가 결과 문서화

**Result**

- Whisper Large-v3-turbo 기반 최종 STT 모델 선정
- Fixed100 WER **7.68%**, CER **1.44%**
- New500 WER **10.72%**, CER **2.26%**
- 요리 도메인 핵심정보 종합 성공률 **96.23%**
- 팀 GPU 환경에서 실시간 추론 구조 검증
- 개인 STT 개발 과정과 평가 결과를 별도 Repository에 정리

TTS 모델 개발과 학습은 팀 프로젝트의 별도 담당 영역이며, 본인은 TTS 출력 음성을 STT 평가에 활용하는 통합 테스트를 진행했습니다.

---

## 🤝 Team Projects

| Project | Role | Tech | Status |
|---|---|---|---|
| 👨‍🍳 **[ChefEar](https://github.com/leeony2636/Chefear-stt)** | STT 모델 개발·평가·경량화·팀 통합 테스트 | Whisper · QLoRA · CTranslate2 · faster-whisper | ✅ STT 개발·팀 GPU 추론 검증 |
| 🧩 **[방탈출 카페 운영 보조 Agent](https://github.com/leeony2636/proj2-1_leeony)** | 팀 프로젝트 참여 | FastAPI · MCP · React · TypeScript · OpenRouter | 🚧 개발 중·모델 평가 준비 |

---

## 🚀 Personal Projects

| Project | Description | Tech | Status |
|---|---|---|---|
| 🎵 **[AI Music Genre Classifier](https://github.com/leeony2636/ai-music-final)** | WAV 기반 10개 음악 장르 분류 | Python · PyTorch · ResNet18 · Streamlit | ✅ 모델 개선·Streamlit 배포 |
| 🤖 **[GitHub Weekly Three-Model Project Reviewer](https://github.com/leeony2636/github-weekly-project-reviewer)** | 세 모델 독립 분석·교차검증, 주간 리뷰·PR 리뷰 | Python · GitHub Actions · Multi-AI · SQLite | ✅ 리뷰 워크플로우 구성 |
| 🐳 **[Docker FastAPI Multi-AI API](https://github.com/leeony2636/docker-fastapi-sentiment-api)** | 감정분석·AI 채팅·이미지 설명 API | Python · FastAPI · Docker · Hugging Face · OpenRouter | ✅ API 구현·Docker 실행 |
| 📊 **[Mini Project - Classification & Regression](https://github.com/leeony2636/Miniproject)** | MNIST CNN 분류·자전거 수요 MLP 회귀·통합 Showcase | Python · PyTorch · Streamlit | ✅ 분류·회귀 앱 통합 |
| 📰 **[AI Hot News + 정책 RAG 챗봇](https://github.com/leeony2636/ai-hot-news-rag-agent)** | AI 뉴스 수집·요약, 한국·미국 정책 PDF 검색·비교 | n8n · OpenRouter · Google Sheets · Ollama · RAG | ✅ 뉴스·정책 챗봇 워크플로우 구성 |
| 🌐 **[AI Portfolio & Chatbot](https://github.com/leeony2636/leeony-portfolio)** | 반응형 포트폴리오·프로젝트 상세 화면·멀티턴 AI 챗봇 | React · TypeScript · Vite · Vercel · OpenRouter | ✅ 웹 배포·챗봇 연동 |
| 🗺️ **[부산 맛집 데이터 가이드](https://github.com/leeony2636/busan-restaurant-guide)** | 부산 16개 구·군·음식 종류 필터와 지도 탐색 | Python · Pandas · Streamlit · Folium | ✅ 지도·필터 UI 구현 |

프로젝트는 기능 구현 이후에도 README, 코드 구조, 실행 결과를 지속적으로 정리하고 있습니다.
상태는 각 저장소 README에 기록된 구현·실험·배포 단계를 기준으로 구분합니다.

---

## 📚 Paper Research Archive

개발 구현의 기반이 되는 AI/Deep Learning 논문들을 읽고 분석하는 공간입니다.
Transformer·BERT·LoRA·QLoRA·모델 경량화·Whisper 등 16개 주제의 정리 노트를 기록하고 있습니다.

| Category | Description | Status | Link |
|---|---|:---:|---|
| 📂 **read_and_chewed** | 직관적 비유·시각적 도해·6단계 분석으로 정리한 AI 논문 아카이브 | 📚 16개 주제 정리·지속 확장 | [View Folder](https://github.com/leeony2636/read_and_chewed) |

---

## Learning & Experiments

프로젝트 개발에 필요한 기술을 직접 실습하고 결과를 기록하고 있습니다.

### AI / Deep Learning

- CNN 이미지 분류
- ResNet18 Fine-tuning
- Transfer Learning
- Data Augmentation
- SpecAugment
- Model Optimization

### NLP / Transformer

- Transformer 구조 실습
- SentenceTransformer
- 문장 Embedding
- 유사도 기반 검색
- Top-K 검색
- Ollama 임베딩과 Simple Vector Store를 활용한 정책 PDF RAG
- 검색 결과를 활용한 한국·미국 AI 정책 비교

### Voice / Audio AI

- 음성 데이터 처리
- Mel Spectrogram
- 음악 장르 분류
- 팀 프로젝트 TTS 연동 참고
- Audio Feature Extraction
- Whisper STT Fine-tuning
- wav2vec2 비교 실험
- QLoRA 기반 STT 모델 학습
- WER / CER 기반 음성인식 모델 평가
- STT / TTS 통합 테스트

### Data / Machine Learning

- Pandas / NumPy 데이터 처리
- RandomForest
- Scikit-learn
- 데이터 시각화
- 모델 성능 비교 및 실험
- MNIST CNN 분류·자전거 수요 MLP 회귀
- 데이터 표준화와 학습 모델의 Streamlit 앱 통합
- 지역·음식 종류 필터와 Folium 지도 시각화

### Backend / API

- FastAPI 기반 REST API
- Hugging Face Inference API 연동
- OpenRouter AI 모델 연동
- API Router 구조 분리
- 환경변수 기반 API Key 관리
- Swagger API 테스트
- Docker 실행 환경 구성
- MCP를 활용한 운영 보조 Agent의 권한·동의 경계
- React·TypeScript·Vite 기반 포트폴리오
- Vercel Serverless Function 기반 AI 챗봇 API
- 대화 이력을 포함한 멀티턴 챗봇

### AI Automation

- GitHub Actions 기반 자동화
- Multi-AI 독립 분석
- Cross Review
- Consensus Validation
- API Quota Guard
- GitHub Issue 자동 생성
- SQLite 실행 기록 관리
- 실제 diff·변경 라인·코드 근거 검증
- Pull Request 대상 교차검증
- n8n 기반 RSS 수집·AI 요약·뉴스 챗봇
- Google Sheets와 문서 검색 도구를 연결한 자동화

---

## Tech Stack

### Language & Data

`Python` `TypeScript` `JavaScript` `Pandas` `NumPy`

### AI / Machine Learning

`PyTorch` `Scikit-learn` `CNN` `MLP` `ResNet18`

### Audio AI

`Librosa` `Mel Spectrogram` `Whisper` `wav2vec2` `CTranslate2` `faster-whisper`

### Model Training

`Fine-tuning` `QLoRA` `WER` `CER`

### Visualization & App

`Matplotlib` `Streamlit` `Folium` `React` `Vite`

### Backend & API

`FastAPI` `Pydantic` `HTTPX` `REST API` `MCP` `Docker` `OpenRouter` `Hugging Face API` `Vercel Serverless Functions`

### AI Automation

`GitHub Actions` `n8n` `Google Sheets` `Qwen` `Command A` `Gemini` `Multi-Agent Cross Review` `SQLite` `Ollama` `RAG`

### Development

`VS Code` `Google Colab` `Git` `GitHub` `GitHub Actions` `Docker` `Vercel`

---

## GitHub Workflow

프로젝트가 늘어나더라도 동일한 기준으로 관리할 수 있도록  
GitHub 운영 원칙을 적용하고 있습니다.

### Repository

- 프로젝트별 독립 Repository 운영
- Public Repository 중심 관리
- 프로젝트 목적을 Description에 명확하게 작성

### README

각 프로젝트 README는 다음 구조를 기준으로 작성합니다.

`프로젝트 소개 → 개발 환경 → 주요 기능 → 실행 방법 → 실행 결과 → 개선 사항`

### Commit

작업 내용을 확인하기 쉽도록 의미 있는 Commit Message를 사용합니다.

- `feat` — 기능 추가
- `fix` — 오류 수정
- `docs` — 문서 수정
- `refactor` — 코드 개선
- `style` — 코드 정리

### Branch

- `main` — 최종 버전
- `develop` — 개발 내용 통합
- `feature` — 기능 개발
- `fix` — 오류 수정
- `docs` — 문서 수정

팀 프로젝트에서는 팀별 규칙을 따르며, 방탈출 프로젝트는 작성자 성명 이니셜 + 생성 순번으로 작업 브랜치를 구분합니다.

### Issue / Pull Request

프로젝트 작업 및 협업 과정에서  
Issue → Branch → Pull Request → Merge 흐름을 기록합니다.

### Automated Review

프로젝트 상태를 정기적으로 점검하기 위해  
Qwen · Command A · Gemini 기반의 주간 Multi-AI Review 시스템을 운영하고 있습니다.

세 모델이 최신 핵심 파일과 최근 변경사항을 독립적으로 검토한 뒤,  
실제 코드 근거를 확인하고 서로의 의견을 교차검증합니다.

서로 다른 모델 중 최소 2개가 동의한 항목을 최종 결과로 채택하며,  
모델별 의견·실행 상태·교차검증 결과를 GitHub Issue와 JSON·SQLite 기록으로 남깁니다.

---

## Development Roadmap

AI / Python 기초 학습  
↓  
개인 프로젝트 구현  
↓  
실험 · 성능 개선 · 문서화  
↓  
Streamlit 기반 AI 결과물 배포  
↓  
FastAPI · Docker · MCP 기반 AI API 및 운영 보조 Agent 구현  
↓  
GitHub Actions · n8n 기반 Multi-AI 리뷰 및 뉴스·정책 RAG 워크플로우 구축  
↓  
논문 및 기술 Research Archive 구축  
↓  
STT 개발·팀 통합 테스트 및 운영 보조 Agent 협업 경험 확장  
↓  
React · TypeScript · Vercel 기반 포트폴리오 및 멀티턴 AI 챗봇 고도화
