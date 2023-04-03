## AI Lecture 6 : Logistic Regression
---  
#### **Logistic Regression** : 회귀를 사용하여 데이터가 어떤 범주에 속할 확률을 0에서 1사이의 값으로 예측하고 그 확률에 따라 가능성이 더 높은 범주에 속하는것으로 분류해주는 지도 학습 알고리즘. 2진 분류
* 선형회귀를 쓰는 이유 : 확률이 음과 양의 방향으로 무한대까지 뻗어감. 논리적으로 말이 안됨
* 과정   
  i) data set 통해 Linear model 형성   

![image](https://user-images.githubusercontent.com/127752372/229476235-7eaa6ae8-e952-4f4e-bf26-aa111a5a428a.png)

  ii) sigmoid 함수에 값들을 넣어 [0,1] 사이의 확률로 표현   
  * Sigmoid Function
  $$\sigma={1\over {1+e^{-z}}}$$
  
![image](https://user-images.githubusercontent.com/127752372/229476350-05e9096d-e8c9-4387-a182-6d6dde3c2d03.png)
  
  iV) optimizing   
  cost=> log loss :y=1일 때와 y=0 일때 두 가지로 나눔
  ![image](https://user-images.githubusercontent.com/127752372/229479869-c6390780-e18c-4a6c-a7e5-2468d46847f5.png)

[출처:https://hleecaster.com/ml-logistic-regression-concept/]   
  iii)Threshold 설정
  기본적으로 0.5를 임계점으로 사용   
  
