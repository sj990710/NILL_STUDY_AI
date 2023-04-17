# CNN(Convolutional Neural Network)   
### 이미지의 공간정보를 유지한채 학습   
## 1. Filter   
  이미지의 가로 세로 특징을 뽑아 주는 미니맵. CNN에서는 적합한 필터를 자동으로 골라줌
## 2. Convolution   
  Filter를 통해 이미지의 특징을 추출, stride 값을 설정해 이미지 영역에 Filter를 특정 회수 만큼 적용   
## 3. Padding   
  Filter를 통해 Convolution을 진행하며 map의 크기가 작아지는 것을 방지. 주로 Zerro Padding을 사용=> 특징이나 분해능 변화X
## 4. Pooling
  과도한 연산량을 방지하기 위해 크기를 줄이면서도 특정 Feature를 강조하는 방법.
  1) Max Pooling->CNN에서 주로 Max Pooling 사용(뉴런이 가장 큰 신호에 반응하는 것처럼=>노이즈 감소, 속도 증가, 분별력 상승)  
  2) Average Pooling  
  3) Min Pooling
