 ## **AI 강의 2 : Linear Model**
 ---
 ### Machine Learning-Supervised learning
 * **Model** : 주어진 data set을 통해 Supervised learning 진행
   + Model design : 공부 시간을 통해 받을 점수를 예측한다. Linear Regression. 
   + Variable : x(공부 시간), w(가중치), ŷ(예측 점수), y(실제 점수), loss(오차), MSE(오차의 평균)
 * **Derivation Process**
   1. w 값에 따라 생기는 ŷ값 도출 : ŷ=x*w
   2. 실제 점수 y와 ŷ값의 차이를 통해 loss를 구함
   3. loss의 평균, MSE를 구해 실제 점수 y와 가장 유사한 가중치 w를 찾음
 
