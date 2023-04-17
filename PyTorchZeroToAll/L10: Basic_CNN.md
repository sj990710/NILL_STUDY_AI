# CNN(Convolutional Neural Network)   
#### 이미지의 공간정보를 유지한채 학습   
![image](https://user-images.githubusercontent.com/127752372/232468013-c41e6461-7103-4e8d-a745-f50848b331f7.png)

## 1. Filter   
  이미지의 가로 세로 특징을 뽑아 주는 미니맵. CNN에서는 적합한 필터를 자동으로 골라줌 
## 2. Convolution   
  Filter를 통해 이미지의 특징을 추출, stride 값을 설정해 이미지 영역에 Filter를 특정 회수 만큼 적용   
  
  ![image](https://user-images.githubusercontent.com/127752372/232468197-6e9c3c55-fc31-40e2-a091-16c3ee62f2ca.png)

## 3. Padding   
  Filter를 통해 Convolution을 진행하며 map의 크기가 작아지는 것을 방지.
  주로 Zerro Padding을 사용=> 특징이나 분해능 변화X 
  
  ![image](https://user-images.githubusercontent.com/127752372/232468383-b7453320-586c-4d3b-9fc6-c9751f18de33.png)

## 4. Pooling
  과도한 연산량을 방지하기 위해 크기를 줄이면서도 특정 Feature를 강조하는 방법.
  1) Max Pooling->CNN에서 주로 Max Pooling 사용(노이즈 감소, 속도 증가, 분별력 상승)  
  2) Average Pooling  
  3) Min Pooling  
   
  ![image](https://user-images.githubusercontent.com/127752372/232468505-9773f4b7-8073-47bd-b863-05ae0b94b7bc.png)
