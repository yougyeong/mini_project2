# KBO 빅데이터 머신러닝으로 OPS 예측하기

## Project
- 주제 : 2023 KBO 타자OPS 예측하기
- 팀원 : 오유경, 전희진, 송소정
- 기간 : 2022/09/15 - 2022/09/20
- 발표 : 2022/09/20
- Language : Jupyter notebook

## Data
- https://www.koreabaseball.com/Record/Player/HitterBasic/BasicOld.aspx

## 0. 주제 선정 및 문제 정의
- 야구에는 수많은 지표가 있고 선수 한 명이 팀의 승리를 좌우하는 게임도 아니어서 승리 예측을 하기 어렵다.
- 이 때, 장타율과 출루율을 합친 `OPS` 지표를 활용할 수 있다.
- 타자의 다음시즌 OPS를 예측하는 수치예측 모델로, **Random Forest, XGBoost** 등을 활용하여 예측하였고 성능을 **WRMSE**로 평가했다.

## 1. 탐색적 데이터 분석
- Selenium을 사용한 KBO 데이터 수집.ipynb
- correlations between pre-season and regular season.ipynb
- 2023 KBO OPS PREDICTION.ipynb
### 1.1. 데이터 클렌징
### 1.2. 데이터 시각화
### 1.3. 상관관계 분석


## 2. 데이터 전처리: Feature Engineering

## 3. 베이스라인 모델 구축

## 4. 성능 올리기
### 4.1 Feature Engineering #2
### 4.2. Grid Search, Hyper parameters

## 5. 결론
### 5.1. 최종예측 및 성능평가
### 5.2. 프로젝트 리뷰

## Presentation
- KBO 빅데이터 머신러닝으로 OPS 예측하기.pdf : 2022/09/20 발표 자료
