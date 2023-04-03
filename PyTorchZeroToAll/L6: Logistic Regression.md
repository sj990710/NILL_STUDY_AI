## AI Lecture 6 : Logistic Regression
---  
#### **Logistic Regression** : 회귀를 사용하여 데이터가 어떤 범주에 속할 확률을 0에서 1사이의 값으로 예측하고 그 확률에 따라 가능성이 더 높은 범주에 속하는것으로 분류해주는 지도 학습 알고리즘. 2진 분류
* 선형회귀를 쓰는 이유 : 확률이 음과 양의 방향으로 무한대까지 뻗어감. 논리적으로 말이 안됨
* 과정
  i) data set 통해 Linear model 형성   
  ii) sigmoid 함수에 값들을 넣어 [0,1] 사이의 확률로 표현   
  iii)Threshold 설정   
  iV) optimizing   
  * Sigmoid Function
  $$H(x)={1\over {1+e^{-W^TX}}}$$
