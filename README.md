# car_detect

## 1차 학습 결과
사용 데이터 : [Kaggle](https://www.kaggle.com/sshikamaru/car-object-detection)

도로 주행 영상을 1001개에 이미지로 나눈 데이터를 사용하였다.
밑에 이미지는 학습 후 detect를 시도하였을 때 모습을 보여준다.
해당 모델에서는 차량만을  detect하였다.

<img src="https://github.com/jangByeongHui/car_detect/blob/main/ezgif.com-gif-maker.gif?raw=true">

## 2차 학습 결과
사용 데이터 : [Kaggle](https://www.kaggle.com/sshikamaru/car-object-detection) & 구글 이미지

도로 주행 영상을 1001개에 이미지 구글 이미지를 통해 얻은 사진 300장을 추가
이후 Object를 직접 bounding후 augmentaion으로 총 이미지 데이터 2000장 생성 
마찬가지로 해당 모델에서는 차량만을  detect하였다. 

<img src="https://github.com/jangByeongHui/car_detect/blob/main/test_2.gif?raw=true">