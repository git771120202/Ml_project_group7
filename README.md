# Ml_project_group7

## 분석 대상 논문
### 제목
머신러닝을 활용한 중학생의 학업성취 예측(황수진, 2022)

### 연구의 목적
학생들의 맞춤형 학습을 위한 전통적 통계분석 방법의 한계를 극복하고,
학업성취에 대한 세분화된 과학적 분석을 통해 어떤 요인이 학업성취에
더 중요한 예측력을 가지는지 규명하고자 함

### 연구 방법 및 문제
(a) 연구방법 : KNN, 의사결정나무, 랜덤포레스트, SVM 등을 활용하여
    중학생의 학년별/과목별 학업성취를 예측하고, 분석결과 비교분석
    
(b) 연구문제 : 중학생들의 학업성취를 여러 머신러닝 기법들로 예측했을 때,
    가장 좋은 성능을 가진 기법과 주요 예측요인들은 무엇인가?

### 분석 대상 및 자료
경기교육종단연구 초등패널 4차~6차(2015~2017년, 197개 중학교 대상)

1. 예측 변수 : 학생 관련 394개, 가정배경 관련 45개, 학교관련 206개(총 645개)
2. 데이터셋 분리 : traning data 80%, test data 20%
3. 검증 지표 : accuracy, sensitivity, specificity, roc, kappa

### 분석 방향
1. 논문에서 제시항 모형별 성능 검증
   : 학년별/과목별 예측모형 평가결과 재현 및 비교
     => KNN, C5.0(의사결정나무), RF, SVM 4개 모델 구현 및 결과 분석
2. 논문의 결과를 보완하기 위한 모델 개선안 제시
2.1 Feature Selection : Correlation, Filter Methods 등을 활용해 모델의 복잡도를 줄이고 중요한 변수만을 선택
2.2 Ensemble Learning : Voting, Bagging, Boosting 등을 활용해 모델의 정확도 향상
