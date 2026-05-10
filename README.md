# 안녕하세요, MJ입니다 👋

**AI 모델 개발부터 API 서버 구축, 실시간 데이터 처리, Docker 배포까지 — End-to-End AI 시스템을 만드는 엔지니어입니다.**

---

## 핵심 역량

| 영역 | 기술 |
|------|------|
| **Computer Vision** | YOLOv8, SAM, DepthAnything, MediaPipe, OpenCV |
| **LLM / Agent** | LangGraph, LangChain, RAG, PEFT, Ollama |
| **ML / AI** | PyTorch, Scikit-learn, IsolationForest |
| **Backend** | FastAPI, WebSocket, MQTT, SQLite |
| **Infra** | Docker, Docker Compose, Linux |
| **Language** | Python (주력), SQL |

---

## 주요 프로젝트

### 🤖 [Multimodal Analysis Agent](https://github.com/MJHolics/multimodal-analysis-agent)
> LangGraph 기반 멀티에이전트 이미지 분석 파이프라인

- 이미지 + 질문 입력 → Orchestrator가 경로 자동 결정 → 구조화된 분석 리포트 출력
- **Vision 팀** (YOLO/SAM/DepthAnything) + **RAG 팀** (ChromaDB) 병렬 협력
- FastAPI REST API + SSE 스트리밍 + Docker 배포
- `LangGraph` `ChromaDB` `YOLO` `SAM` `FastAPI` `Docker`

---

### 🏭 [Industrial Anomaly Detection](https://github.com/MJHolics/industrial-anomaly-ai)
> IoT 센서 기반 실시간 이상탐지 End-to-End 시스템

- MQTT 센서 데이터 → IsolationForest 이상탐지 → WebSocket 실시간 대시보드
- REST API (`/detect`, `/model/train`, `/stats`) + WebSocket + SQLite 로그
- Docker Compose로 Mosquitto + FastAPI + Streamlit 3개 서비스 통합 배포
- `IsolationForest` `FastAPI` `MQTT` `WebSocket` `Streamlit` `Docker`

---

### 🚗 [Driver Monitoring System Agent](https://github.com/MJHolics/dms-agent)
> 실시간 운전자 상태 감지 멀티에이전트 시스템

- 웹캠 영상 → EAR/MAR/PERCLOS + YOLOv8 → LangGraph 에이전트 판단 → 경고 레벨 출력
- 자율주행 경험(YOLO/MediaPipe)을 LangGraph 에이전트 구조에 결합
- Ollama 로컬 LLM으로 API 비용 없이 실시간 추론 (RTX 4080 Super)
- `MediaPipe` `YOLOv8` `LangGraph` `Ollama` `FastAPI` `Docker`

---

## 학습 방식

단순히 모델을 학습시키는 것에 그치지 않고, **실제 서비스 가능한 형태**로 만드는 것을 목표로 합니다.

- 각 프로젝트는 **Notebook으로 개념 탐색 → API 서버 구현 → Docker 배포** 순서로 진행
- 코드 설명보다 **왜 이 구조를 선택했는지**를 커밋 메시지와 README에 기록

---

## 관심 분야

자율주행, 산업 AI, Edge AI, 실시간 영상 처리

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MJHolics&show_icons=true&theme=default&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MJHolics&layout=compact&hide_border=true&langs_count=6" height="150"/>
</div>
