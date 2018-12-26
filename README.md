
# 경북대학교 2018 SW 스킬업 해커톤 1위 수상작 '버드아이저'

* 본 작품은 2018년 8월 바나나코딩이 주최하고 경북대학교 PRIME 사업단이 주관한 SW 스킬업 해커톤에서 최우수상(1위)을 수상한 칠면조 팀의 버드아이저 프로젝트에 관한 코드와 개발 문서 입니다.

## 주의사항

<img width="429" alt="2018-12-26 2 37 18" src="https://user-images.githubusercontent.com/43809168/50433641-c926ac80-091c-11e9-9d3f-063aedd4fa3e.png">


* main.py는 train 후 predict를 시작합니다. 그렇기 때문에 train이 되었다면 train에 관한 코드를 주석처리 해야합니다.
* 위의 사진에 보이는 주석처리 된 코드가 train과 predict를 실행하는 코드 입니다.

## 실행 방법

1. main.py를 실행하여 images 폴더 안의 딥러닝 모델을 학습시킴. 

2. 아두이노의 카메라 모듈을 사용하여 사진을 찍고 Serial 통신으로 파이썬(데스크톱)으로 전송함.

3. 총 5장의 사진이 predict에 쌓이면 예측을 시작하고 학습된 모델이 있는지 여부를 판단하고 있으면 레이저를 발사함.

## 딥러닝 모델 출처 : https://github.com/tensorflow/models/tree/master/research/inception
