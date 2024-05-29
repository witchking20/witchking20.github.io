---
layout: default
title: AI개요
parent: AI
nav_order: 1
---


# Machine Learning
## 기계학습
- 지도학습 
- 비지도학습

## 지도학습
- 분류 (Classification)
- 추청 (Estimation)

## 비지도학습
- 차원축소 (Demension Reduction)
- 군집화 (Clustering)
- 연관성 규칙 발견 (Association Rule)

## 사이킷-런(Scikit-learn)
- 모델 객체 생성 // ...Classifier() or ...Regression()
- 모델에 학습 // model.fit(X_train)
- 예측 // model.predict(X_test)
- 평가 // model.score(X_test,Y_test)

# 머신러닝 용어
## 지도학습(Supervised Learning)
- 학습 데이터에 정답이 포함된 것을 이용하여 학습하는 것(회귀, 분류)
## 비지도 학습(Unsupervised Learning)
- 학습 데이터에 정답이 포함되지 않은 것을 이용하여 학습하는 것(군집)
## 회귀(Regression)
- 하나 또는 그 이상의 특성(독립변수)을 통해 연속적인 숫자로 이루어진 정답(종속변수)를 예측
- 정답은 연속적인 값(수치)
- 주식가격,관객 수, 연봉 등을 예측
## 분류
- 데이터 세트에 미리 정의된 여러 클래스(종류) 중 하나의 클래스를 예측하는 것
- 정답은 예측하려는 데이터가 하나의 클래스에 속한다는 것을 표현(단일 값)
- 숫자 판별, 이미지 판별, 얼굴 인식 등
- 이지(Binary) 분류(두 개의 범주)
- 다중(Multi-class) 분류(세 개 이상의 범주)

# 머신러닝 용어2
## 과소 적합(Under Fitting)
- 모델이 너무 단순하여 데이터의 내재된 구조를 학습하지 못하는 경우
## 과소 적합 해결
- 파라미터가 더 많은 복잡한 모델을 선택하기
- 모델의 제약을 줄이기(규제 하이퍼 파라미터 값 줄이기)
- 과대 적합(Over Fitting)되기 전 시점까지 충분하게 학습시키기
## 과대 적합(Over Fitting)
- 모델이 훈련 데이터에는 너무 잘 맞으나 일반성이 떨어짐
- 훈련 데이터에만 잘 맞으므로 훈련데이터 이외의 다양한 변수에 대응이 어려움
- 모델의 복잡도가 필요 이상으로 높아지는 문제
## 과대적합 해결
- 훈련 데이터 양을 증가 시키기
- 정규화(Regularization)
# 지도 학습 모델 종류  
![스크린샷(19)](https://github.com/witchking20/witchking20.github.io/assets/40237652/cfee022c-8f80-4a63-a0a8-8295abd21ac9)

# 머신 러닝 모델링 주요 개념
![스크린샷(20)](https://github.com/witchking20/witchking20.github.io/assets/40237652/f3a8785e-cd4d-444f-96f6-bf0339de55bf)
