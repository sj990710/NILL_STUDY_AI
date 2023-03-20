 ## **AI 강의 2 : Linear Model**
 ---
 ### Machine Learning-Supervised learning
 * **Model** : 주어진 data set을 통해 Supervised learning 진행
   + Model design : 공부 시간을 통해 받을 점수를 예측한다. Linear Regression. 
   + Variable : x(공부 시간), w(가중치), ŷ(예측 점수), y(실제 점수), loss(오차), MSE(오차의 평균)
 * **Derivation Process**

i) w 값에 따라 생기는 ŷ값 도출

### $ŷ = x \times y$


   |Hours(x)|Points(y)|Points_Pred(ŷ)|
   |---|---|---|
   |1|2|w|
   |2|4|2w|
   |3|6|3w|

ii)  실제 점수 y와 ŷ값의 차이를 통해 loss를 구함 

### $loss = (ŷ - y) = (x \times w - y)$

   |Hours, x|Loss (w=0)|Loss (w=1)|Loss (w=2)|Loss (w=3)|Loss (w=4)|
   |---|---|---|---|---|---|
   |1|4|1|0|1|4|
   |2|16|4|0|4|16|
   |3|36|9|0|9|36|

iii) loss의 평균, MSE를 구해 실제 점수 y와 가장 유사한 가중치 w를 찾음 1\over N
  
## $MSE =$ $1\over N$ $\sum_{n=1}^N$ $(\hat{y}_n - y_n)^{2}$

   |Hours, x|Loss (w=0)|Loss (w=1)|Loss (w=2)|Loss (w=3)|Loss (w=4)|
   |---|---|---|---|---|---|
   |''|18.7|4.7|0|4.7|18.7|

