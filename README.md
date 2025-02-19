# NVIDIA-Jetson-AGX-Xavier
> NVIDIA Jetson AGX Xavier 환경에서 경량화된 실시간 안전모 탐지 모델 개발
---

#### 📖 개요
이 프로젝트는 NVIDIA Jetson AGX Xavier 환경에서 경량화된 실시간 안전모 탐지 모델을 개발하여 산업현장 및 공공안전 분야에서의 안전사고 예방에 기여합니다. YOLOv5 모델을 활용하여 안전모 착용 여부를 실시간으로 탐지하며, 경량화된 구조로 임베디드 환경에서도 높은 성능을 발휘합니다.

#### 📌 주요 내용
- 모델: YOLOv5s (경량화된 버전)
- 플랫폼: NVIDIA Jetson AGX Xavier
- 데이터셋: 약 7,000장의 안전모 관련 이미지
- 클래스: head, helmet, person
- 성과:
  - 다양한 각도와 자세에서도 안전모 착용 여부를 정확히 탐지
  - 실시간 객체 탐지 속도와 정확성 간의 최적화 달성
#### 🛠️ 활용 사례
- 건설현장: 작업자의 안전모 착용 여부 모니터링
- 공공안전: 전동 킥보드 및 자전거 이용자의 안전모 착용 감지
- 산업현장: 개인안전장비(PPE) 착용 여부 점검
#### 🚀 연구 특징
- YOLOv5 모델을 기반으로 경량화된 구조를 적용하여 임베디드 환경에서 실시간 동작 가능
- 안전모 외 추가적인 PPE(예: 고글, 조끼, 벨트) 탐지를 위한 확장 가능성 제시
#### 🔮 향후 연구
- YOLOv5 이외의 최신 모델 도입 및 성능 비교
- 화재 예측, 건물 균열 탐지 등 다른 산업 응용 분야로의 확장 연구
#### ✔︎ 결과
- Model mAP
<img src="https://github.com/user-attachments/assets/1a91793a-33bb-475a-bf36-d143f976ecf1" width="500" height="200">

- 앞모습
<img src="https://github.com/user-attachments/assets/1bf07d4c-a17f-4d54-9765-7cea88766f54" width="600" height="300">

- 뒷모습
<img src="https://github.com/user-attachments/assets/ec9b2502-8a2e-4e17-82ce-e0b61b07f31c" width="600" height="300">

- 옆모습, 앉은 모습
<img src="https://github.com/user-attachments/assets/96dac754-585a-46f5-845b-1c061c497b2d" width="600" height="300">



