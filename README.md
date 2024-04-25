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
