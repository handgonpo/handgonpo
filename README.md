<!-- GitHub Profile README | github.com/handgonpo/handgonpo -->

<div align="center">

# AI Backend · Vision AI · Edge AI

### From AI Research to Real-World Systems & Education

**AI 백엔드와 컴퓨터 비전, 산업용 Edge AI를 하나의 서비스로 연결하는 개발·연구·교육 전문가**

Python · Django REST Framework · FastAPI · PyTorch · OpenCV · YOLO · Docker · AWS

[**Projects**](#-selected-projects) · [**Expertise**](#-core-expertise) · [**Tech Stack**](#-tech-stack) · [**Education**](#-research--education)

</div>

---

## 👋 About Me

**제가 만드는 것은 개별 AI 모델이 아니라, 현장에서 동작하고 검증할 수 있는 End-to-End AI 시스템입니다.**

Python 기반 API 서비스, 객체검출·자세추정·동작인식, LLM/RAG, Unity·Unreal Engine 시뮬레이션을 연결합니다. 데이터 설계와 모델 평가에서 끝내지 않고 **실시간 추론 → API·디바이스 연동 → Cloud·Edge 배포 → 모니터링·기술문서화**까지 일관된 흐름으로 설계하는 데 강점이 있습니다.

AI·Big Data 석사 학위와 DBA 과정의 연구 경험을 바탕으로, 개발·R&D PM/PL·프로젝트 기반 교육(PBL)을 함께 수행해 왔습니다.

| 경험 및 작업 범위 | 확인 가능한 규모 | 의미 |
| :--- | :---: | :--- |
| 개발·교육·멘토링 | **16년+** | 실무형 커리큘럼 설계 및 프로젝트 지도 경험 |
| Vision AI 교육과정 구성 | **교과 7–15 / 9개 교과** | 라벨링 → 객체검출 → 머신비전·Pose → Edge → 최종 프로젝트 연계 |
| 동작인식 교육용 데이터 구성 | **3명 · 6개 동작 · 18개 클립** | Subject-wise Train / Validation / Test 분리 실습 |

> 위 수치는 **경력 및 교육용 프로젝트의 범위**입니다. 모델 성능, 운영 비용 절감, 서비스 사용자 수 등의 실측 성과를 뜻하지 않습니다.

## 🚀 Selected Projects

**관심 기술보다 실제 문제·구현 과정·재현 가능한 결과를 먼저 보여줍니다.**

| Project | Problem & Contribution | Stack / Evidence |
| :--- | :--- | :--- |
| [**Pose & Action Recognition**](https://github.com/handgonpo/subject10_pose_action) | 웹캠·동영상에서 Keypoint를 추출하고, 시간 흐름에 따른 동작 분류·데이터 보강·성능 비교를 실습 가능한 파이프라인으로 구성 | Python, YOLO Pose, OpenCV, scikit-learn / **6 Actions · 3 Subjects · 18 Clips** |
| [**Vision AI Learning & Projects**](https://github.com/handgonpo/Vision_AI_Class) | 머신비전, 자세추정, 합성데이터, VICON, Edge AI, 제조·산업안전 프로젝트를 연결한 실습형 교육 자료 | OpenCV, PyTorch, YOLO, FastAPI, Raspberry Pi, Jetson / **교과 7–15** |
| [**AI Restaurant Backend**](https://github.com/handgonpo/AIRestaurant) | 외부 장소 데이터 수집·관리와 AI 추천 서비스의 백엔드·API 및 배포 구조를 개발·실습 | Django, DRF, FastAPI, MySQL, Docker, AWS EC2, GitHub Actions |
| [**DICONAI Data Platform**](https://github.com/handgonpo/diconai-projects) | 센서 데이터 수집부터 저장·분석·알림·모니터링까지 이어지는 데이터 서비스 구조를 다루는 프로젝트 | DRF, FastAPI, PostgreSQL, Redis, Celery, Docker Compose, Prometheus, Grafana |

> 각 저장소는 서로 다른 **프로젝트·실습 단계**를 보여줍니다. 상용 서비스 운영 성과와 교육용 PoC를 동일하게 표현하지 않았습니다.

## 🎯 Core Expertise

| Focus | What I Build / Design |
| :--- | :--- |
| **AI Backend · LLM/RAG** | Django REST Framework·FastAPI 기반 REST API, 인증, AI 모델 서빙, 검색·질의응답 연동 |
| **Computer Vision · Action Recognition** | OpenCV·YOLO·MediaPipe 기반 객체검출, Pose/Keypoint, Skeleton, 시계열 동작 분류 |
| **Industrial Vision · Edge AI** | 산업용 카메라·조명·컨베이어 연동 구조, 검사 결과 시각화, ONNX·TensorRT, Jetson·Raspberry Pi |
| **Cloud · DevOps · Observability** | AWS EC2·S3·G5, Docker·Kubernetes, GitHub Actions CI/CD, Prometheus·Grafana 모니터링 |
| **XR · Simulation · Motion Capture** | Unity·C#, Unreal Engine, Blender, VICON 모션 데이터 및 3D 시각화 |
| **R&D · PBL Education** | 요구사항·아키텍처·데이터셋·성능평가·기술문서를 연결하는 프로젝트 기획과 실습 교육 |

## 🔄 End-to-End AI Development

```mermaid
flowchart TB
    A["01 · Plan & Architecture<br/>요구사항 · 데이터/서비스 설계"]
    B["02 · Data & Quality<br/>수집 · 촬영 · 라벨링 · QA"]
    C["03 · Model & Evaluation<br/>객체검출 · Pose · 동작인식<br/>Accuracy / F1 / mAP"]
    D["04 · Serving & Optimization<br/>DRF · FastAPI · 실시간 API<br/>ONNX · TensorRT"]
    E["05 · Cloud / Edge Integration<br/>AWS · Jetson · Raspberry Pi<br/>카메라 · 컨베이어 · 센서"]
    F["06 · Operations & Evidence<br/>추론 결과 · FPS · 로그<br/>Prometheus · Grafana · 문서화"]

    A --> B --> C --> D --> E --> F
    F -. "현장 데이터·오류 분석을 개선에 반영" .-> B

    classDef plan fill:#E8EAF6,stroke:#3949AB,color:#1A237E,stroke-width:1.5px
    classDef data fill:#E3F2FD,stroke:#1976D2,color:#0D47A1,stroke-width:1.5px
    classDef model fill:#E8F5E9,stroke:#388E3C,color:#1B5E20,stroke-width:1.5px
    classDef serving fill:#FFF3E0,stroke:#EF6C00,color:#BF360C,stroke-width:1.5px
    classDef edge fill:#F3E5F5,stroke:#8E24AA,color:#4A148C,stroke-width:1.5px
    classDef ops fill:#E0F2F1,stroke:#00897B,color:#004D40,stroke-width:1.5px
    class A plan
    class B data
    class C model
    class D serving
    class E edge
    class F ops
```

## 🛠 Tech Stack

**Core:** Python · Django/DRF · FastAPI · PyTorch · OpenCV · YOLO · Docker · AWS · ONNX/TensorRT

<details>
<summary><b>전체 기술 스택 보기 · 8개 분야</b></summary>

### Backend / API

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Django Channels](https://img.shields.io/badge/Django_Channels-092E20?style=flat-square&logo=django&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-00599C?style=flat-square)

### Frontend / Web

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)

### Database

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### DevOps / Cloud / Monitoring

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![AWS EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![AWS S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![AWS EC2 G5](https://img.shields.io/badge/EC2_G5_GPU-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### AI / Data / Vision

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat-square&logo=ultralytics&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Transformers](https://img.shields.io/badge/Transformers-FFCC4D?style=flat-square)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Beautiful Soup](https://img.shields.io/badge/Beautiful_Soup-59666C?style=flat-square)

### AI Deployment / Edge AI

![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)

### XR / Simulation / Motion Capture

![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![C Sharp](https://img.shields.io/badge/C%23-512BD4?style=flat-square)
![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white)
![VICON](https://img.shields.io/badge/VICON-243746?style=flat-square)

### Collaboration / Development Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square)
![Insomnia](https://img.shields.io/badge/Insomnia-4000BF?style=flat-square&logo=insomnia&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)

</details>

## 🎓 Research & Education

**문제 정의 → 구현 → 검증 → 문서화까지 학생이 스스로 완성하도록 설계하는 실습형 교육**을 지향합니다.

- **2026.10–현재** · 현장 데이터 기반 Vision AI & 산업분야 Vertical AI 과정 교육
- **2025.11–2026.07** · AI 활용 Python 프로덕트 개발 과정 주강사
- **2024.03–2025.06** · 국민대학교 캡스톤 연구수업 멘토링
- **2019.08–2022.07** · IT 교육과정 운영 및 Program Director

### Quantified Project Criteria (교육과정 설계 목표 · 실측 성과 아님)

| 교육 프로젝트 | 설계·평가 기준 |
| :--- | :--- |
| **제조 Vision AI** | 최소 **5개 검출 클래스**, 이미지 **500장 이상**, 목표 **mAP@0.5 ≥ 0.70 / 20 FPS 이상** |
| **산업안전 Action AI** | 최소 **10개 동작**, 목표 **Top-1 Accuracy 약 80% / 30 FPS 이상** |
| **기초 Pose 실습** | **3 Subjects × 6 Actions = 18 Clips**, Subject-wise Split |

> 목표치는 교육 프로젝트의 **요구사항·평가 기준**이며, 실제 달성한 모델 성능으로 표기하지 않습니다. 실측 결과는 해당 프로젝트의 평가 리포트로 확인합니다.

## 🤝 Collaboration

AI 백엔드·Vision AI·산업용 Edge AI·XR 시뮬레이션 및 **AI 융합 R&D / PBL 교육** 분야의 협업에 관심이 있습니다.

- [GitHub Projects](https://github.com/handgonpo?tab=repositories)
- 이슈·프로젝트 제안은 각 저장소의 Issues 또는 GitHub 프로필에 공개된 연락처를 이용해 주세요.

---

<div align="center"><sub>Build · Evaluate · Deploy · Monitor · Document · Teach</sub></div>
