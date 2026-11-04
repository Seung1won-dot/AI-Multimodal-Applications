# AI 활용 멀티모달 & MCP PJ1 시즌1

파이썬 기초부터 데이터 분석, 머신러닝·딥러닝, 멀티모달 AI, LangGraph 에이전트까지 단계별로 실습한 Jupyter 노트북 모음입니다. 강의를 들으며 정리한 개인 학습 기록입니다.

| 항목 | 내용 |
|------|------|
| 학습 목표 | 파이썬 문법 → 데이터 분석 → ML/DL → NLP·비전·멀티모달 모델 → LLM 에이전트까지 흐름을 직접 코드로 익히기 |
| 학습 범위 | 5단계 · 노트북 67개 (각 폴더에 단계별 `README.md`) |
| 형태 | 개인 학습 (강의 실습) |
| 기술 스택 | Python 3 · Google Colab / Jupyter · NumPy · Pandas · Matplotlib · scikit-learn · PyTorch · TensorFlow · Hugging Face Transformers · LangChain · LangGraph |
| 저장소 정리 | 2026-03 업로드, 2026-10 README 정리 |
| 상태 | 시즌1 완료 |

## 목차

- [단계별 구성](#단계별-구성)
- [노트북 목록](#노트북-목록)
- [시작하기](#시작하기)
- [프로젝트 구조](#프로젝트-구조)
- [더 읽을거리](#더-읽을거리)

## 단계별 구성

| 순서 | 폴더 | 무엇을 배웠나 |
|------|------|------|
| 1 | [1. 파이썬 기초](./1.%20파이썬%20기초) | 변수·컬렉션·제어문·함수·클래스·예외처리 |
| 2 | [2. 데이터 분석](./2.%20데이터%20분석) | NumPy·Pandas·Matplotlib, 공공·Kaggle 데이터 EDA, Selenium 크롤링 |
| 3 | [3. 머신러닝-딥러닝](./3.%20머신러닝-딥러닝) | scikit-learn 회귀·분류, PyTorch·TensorFlow, MLP·CNN·AlexNet |
| 4 | [4. 멀티모달](./4.%20멀티모달) | 벡터화·RNN·어텐션·트랜스포머·PLM, ViT·오토인코더, CLIP·DINO·BLIP |
| 5 | [5. AI Agent](./5.%20AI%20Agent) | LangGraph 기초 문법, 챗봇, Reflection 패턴 |

## 노트북 목록

노트북 파일 이름 앞의 번호가 학습 순서입니다.

### 1. 파이썬 기초

| 번호 | 노트북 |
|------|--------|
| 1 | 구글 코랩 |
| 2~4 | print 함수, 파이썬의 변수, 문자열 다루기 |
| 5~8 | 컬렉션 타입 — 리스트, 튜플, 딕셔너리, 세트 |
| 9 | 파이썬 연산자 |
| 10~13 | input 함수, 제어문(조건문·반복문), 컬렉션과 반복문 |
| 14~16 | 사용자 정의 함수, 변수의 범위, 콜백함수와 람다함수 |
| 17~18 | 객체지향과 클래스, 파이썬의 상속 |
| 19~20 | 스페셜(매직) 메소드, 예외처리 |

### 2. 데이터 분석

| 번호 | 노트북 |
|------|--------|
| 0 | 파이썬 모듈 (실습용 `module/` 폴더: `math_tools.py`, `shapes` 패키지) |
| 1~3 | 넘파이, 판다스, matplotlib |
| 4 | Online Retail 데이터 살펴보기 |
| 5 | 소상공인시장진흥공단 상가정보 데이터셋 |
| 6 | 서울시 공공자전거 실시간 대여정보 |
| 7 | 셀레니움 |
| 9 | 커피 프랜차이즈의 입점전략 |
| 10 | 깃허브로 일괄 업로드 |
| 11 | 네이버증권 |

### 3. 머신러닝-딥러닝

| 번호 | 노트북 |
|------|--------|
| 1~2 | 머신러닝, 사이킷런 |
| 3~5 | 주택 임대료, 서울 자전거 공유 수요 예측, 호텔 예약 수요 데이터셋 |
| 6~9 | 파이토치 프레임워크, 선형 회귀, 논리 회귀, 손 글씨 숫자 데이터셋 |
| 10~12 | 퍼셉트론과 다층 퍼셉트론, Multi-class Weather Dataset, CNN |
| 13~15 | 손글씨 도형 분류, AlexNet 구현, Alien vs. Predator 데이터셋 |
| 16 | 텐서플로우 |

### 4. 멀티모달

| 번호 | 노트북 |
|------|--------|
| 1~3 | 자연어 처리, 벡터화, 신경망 기반의 벡터화 |
| 4~6 | RNN, LSTM과 GRU, Seq2Seq |
| 7~9 | 어텐션 메커니즘, 트랜스포머, 사전 학습된 언어 모델(PLM) |
| 10 | A Multi-label Hate Speech Detection Dataset |
| 11~12 | Vision Transformer(ViT), 오토인코더 |
| 13~14 | 멀티모달, CLIP |
| 15 | 차원 축소 |
| 16~17 | DINO, BLIP |

### 5. AI Agent

| 번호 | 노트북 |
|------|--------|
| 3 | 랭그래프 기초 문법 |
| 4 | 랭그래프를 이용한 간단한 챗봇 |
| 5 | 랭그래프 Reflection |

## 시작하기

모든 노트북은 Google Colab 기준으로 작성했습니다.

1. Colab의 **파일 → 노트북 열기 → GitHub** 탭에서 이 저장소의 노트북을 열거나, 저장소를 내려받아 Jupyter에서 엽니다.
2. 데이터셋은 용량 문제로 저장소에 없습니다. 각 폴더의 `data/DATA_SOURCES.md`에서 내려받아 같은 `data/` 폴더에 넣습니다.
3. 노트북 위에서부터 차례로 실행합니다. Colab에 기본으로 없는 패키지는 해당 노트북의 `pip install` 셀에서 설치합니다.

```bash
git clone https://github.com/Seung1won-dot/AI-Multimodal-Applications.git
```

## 프로젝트 구조

```text
AI-Multimodal-Applications/
├── 1. 파이썬 기초/          노트북 1~20
├── 2. 데이터 분석/          노트북 0~11
│   ├── data/DATA_SOURCES.md  데이터셋 내려받기 링크
│   └── module/               모듈 실습용 math_tools.py, shapes/
├── 3. 머신러닝-딥러닝/      노트북 1~16
│   └── data/DATA_SOURCES.md
├── 4. 멀티모달/             노트북 1~17
└── 5. AI Agent/             노트북 3~5
```

## 더 읽을거리

- 단계별 정리: [1. 파이썬 기초](./1.%20파이썬%20기초/README.md) · [2. 데이터 분석](./2.%20데이터%20분석/README.md) · [3. 머신러닝-딥러닝](./3.%20머신러닝-딥러닝/README.md) · [4. 멀티모달](./4.%20멀티모달/README.md) · [5. AI Agent](./5.%20AI%20Agent/README.md)
- 데이터 출처: [2. 데이터 분석/data/DATA_SOURCES.md](./2.%20데이터%20분석/data/DATA_SOURCES.md) · [3. 머신러닝-딥러닝/data/DATA_SOURCES.md](./3.%20머신러닝-딥러닝/data/DATA_SOURCES.md)
