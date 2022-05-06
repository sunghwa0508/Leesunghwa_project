# Project 소개

해당 프로젝트는 고객의 다양한 데이터를 바탕으로

인사이트도출 및 비즈니스적 의사결정을 하고 분류 모델 및 이상탐지을 구현하는 것을 목표로 하였습니다.

----------------------------------------------------------------------------------------------------------------------------------------------
# Anomaly Detection project 이상 탐지 프로젝트

<목적> 

고객의 신용카드 내역을 분석하여 사기 거래를 예측할 수 있는 모델을 만들고자합니다. 

**<사용 데이터> Credit Card Fraud Detection**

'https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud'



<데이터 셋 설명>:

- 2013년 9월 유럽 카드 보유자들이 신용카드로 한 284,807개의 거래 내역

- Class 0: 정상 거래, Class 1: 비정상 거래

- V1~V28 : 고객 개인정보로 V99로 표기


<분석 방법>
해당 데이터 셋은 Class의 값이 0과 1로 사전에 감독된 Supervised learing자료 이므로 XGBoost를 사용하여 분석하였습니다.

Supervised Anomaly Detection

해당 데이터 셋은 Class의 값이 0과 1로 사전에 감독된 Supervised learing자료 이므로 XGBoost를 사용하여 분석하였습니다.

Supervised Learning 방식은 다른 방법 대비 정확도가 높은 특징이 있습니다. 그래서 높은 정확도를 요구로 하는 경우에 주로 사용되며, 비정상 sample을 다양하게 보유할수록 더 높은 성능을 달성할 수 있습니다.

XGBoost(Extreme Gradient Boosting)란?

Boosting : 여러 개의 약한 Decision Tree를 조합해서 사용하는 Ensemble 기법 중 하나입니다. 즉, 약한 예측 모형들의 학습 에러에 가중치를 두고, 순차적으로 다음 학습 모델에 반영하여 강한 예측모형을 만듭니다

XGBoost: Boosting 기법을 이용하여 구현한 Gradient Boost 알고리즘을 병렬 학습이 지원되도록 구현한 라이브러리입니다.


<References>
 (2022)Why Should I Ban You! : X-FDS (Explainable FDS) Model Based onOnlineGame Payment Log

'https://www.koreascience.or.kr/article/JAKO202209537216841.pdf'
 
