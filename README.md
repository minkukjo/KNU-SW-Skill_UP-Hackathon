
# Facial expression recognition using CNN in Tensorflow

## 본 작품은 2018년 8월 바나나코딩이 주최하고 경북대학교 PRIME 사업단이 주관한 SW 스킬업 해커톤에서 최우수상(1위)을 수상한 칠면조 팀의 프로젝트 입니다.

## 딥러닝 모델은 inception_v3를 사용하였습니다.

* main.py는 train 후 predict를 시작합니다. 그렇기 때문에 train이 되었다면 train에 관한 코드를 주석처리 해야합니다.

1. main.py를 실행하여 images 폴더 안의 딥러닝 모델을 학습시킴. 

2. 아두이노의 카메라 모듈을 사용하여 사진을 찍고 Serial 통신으로 파이썬(데스크톱)으로 전송함.

3. 총 5장의 사진이 predict에 쌓이면 예측을 시작하고 학습된 모델이 있는지 여부를 판단하고 있으면 레이저를 발사함.

# inception v3 원 코드 출처 : https://github.com/tensorflow/models/tree/master/research/inception