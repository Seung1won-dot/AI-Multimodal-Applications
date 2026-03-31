# 🤝 AI Agent (LangGraph)

AI 에이전트를 구축하기 위한 LangGraph 프레임워크를 학습하는 과정입니다.

## 📚 학습 내용

### LangGraph 기초
- LangGraph의 기본 문법
- 상태(State) 관리
- 노드(Node)와 엣지(Edge)
- 그래프 구성

### 실전 프로젝트
- **간단한 챗봇**: LangGraph를 활용한 대화형 에이전트
- **Reflection 에이전트**: 자기反省 능력을 갖춘 에이전트

## 📁 LangGraph란?

LangGraph는 LLM(Large Language Model) 기반 에이전트를 구축하기 위한 프레임워크입니다.
LangChain을 기반으로 하며, 에이전트의 작업 흐름을 **Directed Graph** 형태로 설계할 수 있습니다.

### 주요 특징
- **상태 기반**: 각 노드에서 상태를 공유하고 업데이트
- **순환(Cycle) 지원**: 루프와 조건 분기 가능
- **체크포인트**: 상태 저장 및 복원
- **내장 Persistence**: 대화 기록 관리

## 📁 파일 구성

| 파일명 | 내용 |
|--------|------|
| 3. 랭그래프 기초 문법.ipynb | LangGraph 기본 개념 |
| 4. 랭그래프를 이용한 간단한 챗봇.ipynb | 첫 번째 에이전트 프로젝트 |
| 5. 랭그래프 Reflection.ipynb | 고급 Reflection 패턴 |
