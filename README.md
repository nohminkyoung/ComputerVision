# ComputerVision

#### 퍼스트캠퍼스 강의 데이터를 활용한 computervision실습

--------------------------------------------------
## 02.MEDICAL_Classification
- x-ray 데이터를 활용한 정상,코로나,폐렴 분류
- 데이터셋 구성 : 정상(70/20), 코로나(111/26), 폐렴(70/20)


## 03.MEDICAL_Segmentation
- CT 복원 영상에서 특정영역 가이드 하기 (폐,기도,심장)
- 데이터셋 구성 : 112명에 대한 촬영 데이터 16708장 (14910/1798)


## 04.MEDICAL_TransferLearning
- 03과 같은 task
- 16708장 중 240장(120/120)만 활용하여 학습을 진행
- vgg모델을 활용해 네트워크를 구성, pretrained와 weight initialization의 성능 비교


## 05.DRIVING_ObjectDetection
- 차량의 이미지와 boundingbox의 좌표를 이용해서 truck과 bus객체탐지
- 데이터셋 구성 : 13703/1522
- 2-stage-detection인 fasterRCNN모델을 활용한 학습


## 06.DRIVING_AdvancedObjectDetection
- 05와 같은 task
- 차량의 이미지와 boundingbox의 좌표를 이용해서 truck과 bus객체탐지
- 1-stage-detection인 Yolo v1 모델을 구현 및 학습
