# :mag_right: 생체 광학 데이터 AI 분석

## Project Description
빛을 응용한 뇌 내 성분 검사는 피부 상처 없이 다양한 성분 정보를 알 수 있습니다. 이는 뇌 활동 연구를 위해 신경영상을 얻을 수 있는 방법으로, 바늘(전극)을 찔러 넣는 방법인 뇌전도 검사를 대체할 방안으로 각광 받고 있습니다.

이번 저희 프로젝트에서는 신경영상 및 뇌 활동 검사를 위해 제공된 모의 시뮬레이션 데이터를 통해 뇌 내 성분을 분석하는 모델을 만들어봤습니다.

## Data
Dacon(생체 광학 데이터 분석 AI 경진대회)[https://www.dacon.io/competitions/official/235608/overview/description]

## Model
* Linear Regression
* RandomForest
* Xgboost
* DNN

<img src="https://user-images.githubusercontent.com/68156494/136102985-a811332f-1bfa-48d1-beed-a9d22e058f98.png" width="70%" height="80%">


## Conclusion
1. 의의

  신경영상 및 뇌 활동 검사를 위한 Xgboost 기반의 AI 솔루션 제공


2. 한계점

상대적으로 작은 Na농도의 오차가 큼
Feature들간의 sequential 한 관계가 있음=> 추후 RNN을 이용하면 더 성능이 좋아질 것으로 예상됨
