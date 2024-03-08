# Mask-R-CNN-train
Instance Segmentation

Check this video to understand the code: https://www.youtube.com/watch?v=QP9Nl-nw890

![Screenshot 2023-02-18 154952](https://user-images.githubusercontent.com/60029146/219943863-63467d85-db8e-40f8-b712-a31ed89717fb.jpg)

# 사용
customtrain.py (Mask R-CNN 모델을 사용하여 커스텀 객체 탐지 모델을 훈련하는 방법)

1. 라이브러리 불러오기
2. 경로 설정
3. CustomConfig 설정 : gpu 설정, 이미지 당 처리 수, 클래스 수, 에포크 당 스텝 수 등
4. 데이터셋 준비 : CustomDataset 클래스에서 train과 val 설정
5. 모델 준비 및 가중치 불러오기 : Mask R-CNN 모델을 초기화하고 COCO 데이터셋에 대한 사전 훈련 가중치를 불러오기
6. train : 학습률, 에포크 수, 레이어 등을 설정
7. 로그 저장 : 지정된 경로에 저장
