# 🚀 정재종 | Robotics & Software Engineer

__2000.08.08__

__Notion__ : [Notion 포트폴리오](https://twilight-doom-404.notion.site/238830036acd80e39a89d3e312252451?pvs=74)  
GitHub : [github.com/rhrnak999](https://github.com/rhrnak999)  
Email : dbrghl240@gmail.com

> 문제 해결에 집요한 개발자

> 사용자와 로봇의 연결 고리를 고민하는 개발자

> 로봇이 ‘실제’ 움직이는 것 까지의 복잡한 과정을 즐기는 개발자

## 프로젝트 상세내용
| 기간 | 프로젝트명 | 주요 내용 |
|------|------------|------------|
| 2025.06 – 2025.07 | 디지털 트윈 기반 turtlebot3 오토 레이스 | 가상-실제 환경 연동 TurtleBot3 자율주행 시스템 |
| 2025.06 – 2025.06 | 무인 편의점 어시스턴 | AI 비전·음성 인식 기반 무인 편의점 로봇 어시스턴트 |
| 2025.05 – 2025.06 | 요양 보조 로봇 | 초고령 사회의 요양보조 인력 부족 문제 해결을 위한 지능형 협동로봇 시스템 개발 |
| 2025.05 – 2025.05 | 탐라는 로봇 지킴이 | 도로 위의 불법 주정차 차량을 탐지하는 로봇 |

---
📍 디지털 트윈 기반 TurtleBot3 오토 레이스
---
**🔗[소스코드](https://github.com/rhrnak999/Auto_race_Tb3)**   

기간 : 2025.06 – 2025.07
기술스택 : ROS2, Gazebo, PID, Kalman Filter, OpenCV, RViz, MoveIt

디지털 트윈 환경(Gazebo)에서 운전면허 시험장을 구현하고, TurtleBot3가 가상과 실제 환경 모두에서 자율주행을 수행할 수 있도록 개발했습니다.
주행 제어는 HSV 색공간과 Kalman Filter, Hough Transform 등 다양한 알고리즘을 활용하여 구현했습니다.

주요 기능 : Lane Detect Hybrid 알고리즘 구현, PID 속도 제어기 튜닝, GUI 시각화 구성, ArUco 기반 Pick & Place 로직 작성

---
📍 무인 편의점 어시스턴트
---
**🔗[소스코드](https://github.com/rhrnak999/Self_service_store_assistant)**   

기간 : 2025.06 – 2025.06
기술스택 : ROS2, Doosan Robot API, YOLOv11n, LLM, TTS/STT, Pyzbar, MoveJ, GUI

담배 구매 시 반복되는 업무를 자동화한 비전·음성 인식 기반의 협동로봇 시스템입니다. 사용자의 음성 명령을 이해하고, 담배 종류를 시각적으로 인식하며, 바코드 스캔 및 전달까지 수행합니다.

주요 기능 : GUI, TTS/STT, YOLO, 로봇 제어 등을 통합한 완성도 높은 자동화 로봇 시스템

---
📍 요양 보조 로봇
---
**🔗[소스코드](https://github.com/rhrnak999/Patient_assistance)**   

기간 : 2025.05 – 2025.06
기술스택 : ROS2, Doosan Robot API, Python, Teach-Play, Compliance Control

고령화 사회에서 부족한 요양 인력을 보완하기 위한 협동로봇 기반 케어 자동화 시스템입니다. 물건 전달, 자세 교정, 몸 세척 보조를 Teach-Play 및 순응 제어 방식으로 구현하고, 직관적인 GUI도 함께 개발했습니다.

주요 기능 : Teach-Play 동작 로직 설계, 순응 제어, GUI 연동 구성

---
📍 탐라는 로봇 지킴이
---
**🔗[소스코드](https://github.com/rhrnak999/Transportation_robot)**   
기간 : 2025.05 – 2025.05
기술스택 : ROS2, YOLOv11n, OpenCV, 색상 마스킹, Hough Transform, NAV2

불법 주정차 차량 감지 로봇으로, 직선 기반 차선 인식 + 색상 감지를 통해 단속 라인을 식별하고, YOLO를 통해 차량을 탐지합니다. 거리 기반 판단 후 NAV2로 로봇이 차량에 접근하며 단속을 수행합니다.

주요 기능 : 비전 기반 감지, 마스킹 영역 설정, 거리 계산, 자율 주행 연동
