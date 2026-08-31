# 하주성

## 🌐 Portfolio

👉 [웹 포트폴리오 바로가기](https://leeony-portfolio.vercel.app/)

> 다양한 현장에서 쌓은 문제 해결 경험을 바탕으로  
> Python과 AI 기술을 실제 프로젝트로 구현하고 기록하고 있습니다.

---

## About Me

병원, 철강 가공, 특수용접 등 서로 다른 현장에서 문제를 직접 해결해 온 경험을 바탕으로  
현재 Python · AI · Deep Learning 기술을 활용한 개인 및 팀 프로젝트를 개발하고 있습니다.

결과만 남기는 것이 아니라 **실험 → 개선 → 문서화 → 배포** 과정을 GitHub에 기록하며  
프로젝트의 완성도를 지속적으로 높여가는 것을 목표로 하고 있습니다.

### Career Journey

- 🏥 **병원 물리치료 파트** — 4년
- 🏭 **1차 철강 가공** — 2년
- 🔧 **특수용접** — 2년
- 💻 **Python · AI 기반 프로젝트 개발**

---

## Featured Projects

### 🎵 AI Music Genre Classifier

WAV 음악 데이터를 분석하여 **10개 음악 장르를 예측하는 AI 프로젝트**

`Python` `PyTorch` `ResNet18` `Librosa` `Scikit-learn` `Streamlit`

**Development**

- RandomForest 기반 기본 장르 예측 모델 구현
- 장르별 신뢰도 시각화
- 여러 WAV 파일 비교 기능 구현
- 예측 이력 기능 추가
- 3초 Segment 기반 학습 데이터 확장
- ResNet18 Fine-tuning
- Backbone / FC Learning Rate 분리
- SpecAugment 적용
- AS-IS / TO-BE 모델 성능 비교
- Epoch별 학습 과정 시각화
- Streamlit 웹 애플리케이션 통합

**Result**

- Validation Accuracy: **76.47% → 82.32%**
- Model Improvement: **+5.85%p**
- Epoch별 Validation Accuracy / Train Loss / Learning Rate 시각화
- 6강 기본 → 7강 고급 → 8강 Deep Learning 구조로 기능 확장
- WAV 업로드 기반 음악 장르 예측 웹 구현
- Streamlit 배포 완료

[GitHub Repository](https://github.com/leeony2636/ai-music-final)

### 🌐 Live Demo

[AI 음악 장르 예측기 실행하기](https://ai-music-final-mj2gmrph3khrrncd5dbsgb.streamlit.app/)

---

### 👨‍🍳 ChefEar — AI Voice Cooking Assistant

음성으로 레시피를 검색하고 조리 단계를 진행할 수 있도록 설계한 팀 프로젝트입니다.

`Python` `PyTorch` `Whisper` `wav2vec2` `QLoRA` `Streamlit` `Supabase`

**My Role — STT Fine-tuning**

- Whisper Small, wav2vec2, Whisper Large-v3-turbo 비교
- Whisper Large-v3-turbo 기반 QLoRA 파인튜닝
- 요리명·재료명·수량·단위·조리동작 중심의 음성 인식 평가
- Fixed100 / New500 기준 WER·CER 비교
- 최종 STT 모델 선정 및 팀 서비스 통합 테스트
- CTranslate2 int8 및 faster-whisper 기반 추론 구조 검증
- STT 개발 과정과 평가 결과 문서화

**Result**

- Whisper Large-v3-turbo 기반 최종 STT 모델 선정
- Fixed100 WER **7.68%**, CER **1.44%**
- New500 WER **10.72%**, CER **2.26%**
- 팀 GPU 환경에서 실시간 추론 구조 검증
- 개인 STT 개발 과정과 평가 결과를 별도 Repository에 정리

TTS 모델 개발과 학습은 팀 프로젝트의 별도 담당 영역이며, 본인은 TTS 출력 음성을 STT 평가에 활용하는 통합 테스트를 진행했습니다.

[개인 STT 기록 Repository](https://github.com/leeony2636/Chefear)
---

## 🤝 Team Projects

| Project | Role | Tech | Status |
|---|---|---|---|
| 👨‍🍳 **ChefEar** | STT Model Development & Integration | Whisper · QLoRA · Streamlit | ✅ Completed |

---

## 🚀 Personal Projects

| Project | Description | Tech | Status |
|---|---|---|---|
| 🎵 **AI Music Genre Classifier** | WAV 기반 10개 음악 장르 분류 | Python · PyTorch · ResNet18 · Streamlit | ✅ |
| 📊 **Mini Project - Classification & Regression** | 분류·회귀 모델 학습 및 성능 개선 미니프로젝트 | Python · PyTorch · Machine Learning | ✅ |

프로젝트는 기능 구현 이후에도 README, 코드 구조, 실행 결과를 지속적으로 정리하고 있습니다.

---

## 📚 Paper Research Archive

개발 구현의 기반이 되는 최신 AI/Deep Learning 논문들을 읽고 분석하는 공간입니다.

| Category | Description | Status | Link |
|---|---|:---:|---|
| 📂 **read_and_chewed** | 논문 내용을 직접 요약하고 정리하는 Research Archive | ✅ Completed | [View Folder](https://github.com/leeony2636/read_and_chewed) |

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

### Voice / Audio AI

- 음성 데이터 처리
- Mel Spectrogram
- 음악 장르 분류
- TTS 관련 실습
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

---

## Tech Stack

### Language & Data

`Python` `Pandas` `NumPy`

### AI / Machine Learning

`PyTorch` `Scikit-learn` `ResNet18`

### Audio AI

`Librosa` `Mel Spectrogram` `Whisper` `wav2vec2` `Qwen3-TTS`

### Model Training

`Fine-tuning` `QLoRA` `WER` `CER`

### Visualization & App

`Matplotlib` `Streamlit`

### Development

`VS Code` `Google Colab` `Git` `GitHub`

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

### Issue / Pull Request

프로젝트 작업 및 협업 과정에서  
Issue → Branch → Pull Request → Merge 흐름을 기록합니다.

---

## Development Roadmap

AI / Python 기초 학습  
↓  
개인 프로젝트 구현  
↓  
실험 · 성능 개선 · 문서화  
↓  
Streamlit 기반 결과물 배포  
↓  
논문 및 기술 Research Archive 구축  
↓  
팀 프로젝트 및 협업 경험 확장  
↓  
개발자 포트폴리오 고도화
