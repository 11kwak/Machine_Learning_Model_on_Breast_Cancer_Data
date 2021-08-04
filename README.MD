# Machine Learning Model on Breast Cancer Data

## 목표 : K-Nearest Neighbor 모델 구축
## 1. 데이터 전처리 
## 2. K-Nearest Neighbor 모델 구축 
#### - k 개수 선정 " 인접한 학습데이터를 몇 개까지 탐색할 것인가?"
#### - Distance measure 선정 "데이터 간 거리를 어떻게 측정할 것인가?" 
## 3. 예측 결과 평가 및 weighted KNN 구축 
  
## 데이터 구조
### - 데이터: 위스콘신 대학교에서 제공한 유방암 진단결과
### - 관측치 개수: 569개
### - 변수 개수: 32개(ID:진단결과, 30개의 실측변수값)


## 설명변수(원인: 예측값을 설명할 수 있는 변수) 
### - id : 환자 식별 번호
### - radius : 반경(중심에서 외벽까지 거리들의 평균값)
### - texture : 질감(Gray-Scale 값들의 표준편차)
### - perimeter : 둘레
### - area : 면적
### - smoothness : 매끄러움(반경길이의 소극적 변화)
### - compactness : 조그만 정도(둘레^2/면적-1)
### - concavity : 오목함(윤곽의 오목한 정도)
### - points : 오목한 점의 수
### - symmetry : 대칭
### - dimension : 프렉탈 차원(해안선 근사-1)
### - mean : 3~12번 까지는 평균값을 의미
### - se : 13~22번까지는 표준오차를 의미 
### - worst : 23~32는 각 세포별 구분들에서 제일 큰 3개의 값을 평균낸 값


## 반응 변수(결과: 예측하고자 하는 값)
### - diagnosis : 양성여부(Maligant = 1 악성(유방암), Benign=0 양성(단순낭종))



## Tools

- Python 3.9.6
- VSCode

## Credits

- SUANLAB YOUTUBE 

## License
- Just Fan Game, I don't have the copyright on all sounds and photos in the game.
- If there is a copyright issue, please send me an e-mail one1e@naver.com 
- I love all the soccer players. Son7 Fighting!!!
