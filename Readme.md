# SW 창업 아이디어 경진대회

---

# 프로젝트 명  
보행자 감지 및 사고 예방을 위한 개인 이동형 장비 보조 시스템  

# 참여 기간  
2024.12.7 ~ 2024.12.20  

# 참가자
 박진성, 김성연, 김남규

# 개발 목표  
시각장애인 및 교통 약자를 위한 **실시간 보행 안전 보조 시스템**을 설계하여,  
개인 이동형 장비(예: 지팡이, 휴대 장치)에 부착 가능한 형태로 **보행자 감지 및 사고 예방 기능** 제공  
<img width="1145" height="460" alt="image" src="https://github.com/user-attachments/assets/2d2b0486-1162-4c99-a1fa-b3669c115ff6" />

# 기술 스택  
- Computer Vision: YOLOv8 (객체 인식)  
- Python, OpenCV, PyTorch
- MiDaS (객체 깊이 추정)
- Socket Programming (서버–클라이언트 구조)  
- TTS(Text-to-Speech) 모듈 (음성 안내)  

# 수행 작업  
- YOLOv8 모델을 활용한 **보행자 및 이동체(자전거, 오토바이, 킥보드 등) 탐지**
- 칼만 필터 알고리즘 활용하여 **실시간 객체 추적**
- MiDaS 모델을 활용한 **객체 깊이 추정** 
- **실시간 카메라 영상 처리** 및 위험 상황 탐지 로직 구현  
- **음성 안내 시스템**을 통한 사용자 알림 제공  
- 서버–클라이언트 구조 기반 **데이터 통신 및 로그 관리 시스템** 설계
  
# 제안 시스템

## 후방카메라
후방 카메라는 차량 뒤쪽 상황을 실시간으로 촬영하여, 주차나 후진 시 안전을 지원합니다.
<img src="https://github.com/user-attachments/assets/e01d750f-f18b-4d03-9d58-bcbf6578b29b" style="max-width: 100%; height: auto;" />

## 위험도분석
위험도 분석 시스템은 센서 데이터를 기반으로 주변 위험 요소를 평가하고, 운전자에게 경고를 제공합니다.
<img src="https://github.com/user-attachments/assets/cd9ed1bb-ee85-44e3-a32c-87bceafaa830" style="max-width: 100%; height: auto;" />

## 제어 시스템
제어 시스템은 차량의 주행 및 안전 기능을 자동으로 조정하여, 사고 예방과 안정적인 운행을 돕습니다.
<img src="https://github.com/user-attachments/assets/fb35728c-78fe-4328-807a-6e584e153074" style="max-width: 100%; height: auto;" />


# 성과 / 배운 점  
- 창업 아이디어 공모전 출품 및 실현 가능성 검토  
- **실시간 객체 탐지 + 객체 추적 + 깊이 추정** 적용 경험  
- 보행자 안전을 위한 **휴대형 보조 장치 설계 아이디어** 제안  
- 사회적 약자를 위한 **AI 기반 헬스케어/안전 시스템 개발 가능성** 확인  

---



시각장애인을 위한 위험 감지 시스템 사용설명
-----------------------------------------------
1. Server 파일의 server.js 를 실행하여 서버를 실행한다.
2. React-native를 통해 App.tsx 파일을 build 하여 에뮬레이터 또는 디바이스에서 실행한다.
3. Start Capture 버튼을 누른다.
4. Server 파일의 app.py 를 실행한다.
5. 위험감지를 진행한다.
   


# VERSION
- React-native: 0.76
- Metro: 0.81.0
- Android gradle plugin: 8.6.0
- Gradle: 8.10.2
- Python: 3.12.7
- nodejs: 20.11.1
