# Stock data Analysis

## 1. 프로젝트 개요

 본 프로젝트는 2017년 1월부터 2017 6월까지 차세대융합컨텐츠산업협회에서 `IoT데이터분석을 위한 데이터사이언티스트 양성과정`을 수료하면서 진행한 것입니다. 주요 내용은 주식 데이터(분 단위, 틱 단위)를 키움증권 API를 통해 수집하고, 전처리 과정을 거친 후 클러스터링, 히트맵, HMM(Hidden Markov Model)로 주식을 간단하게 예측하였습니다.



## 2. 데이터 수집

- 데이터 수집에는 `키움증권 API`를 이용.
- 아래 wikidocs를 참고함
  - [파이썬으로 배우는 알고리즘 트레이딩](https://wikidocs.net/book/110)



## 3. 데이터

1. 환율(원환율대비외화)
   - `1990년 ~ 2016년`
2. 코스피 일 단위(주요 종목)
   - `상장 이후 ~ 2016년`
3. 코스피200 틱 단위
   - 2017년 4월 19일 ~ 2017년 5월 19일(1달)
   - 텍스트 형식의 약 `758MB`



## 4. 개발환경

- 데이터 수집 이외에는 대부분 `Anaconda Jupyter notebook` 환경에서 분석을 실시.
- `Anaconda Python 3.7 version 64bit`를 이용할 것을 추천. [다운로드](https://www.anaconda.com/distribution/)



## 5. Requirements

- numpy 1.16.5
- pandas 0.25.1
- scikit-learn 0.21.3
- matplotlib 3.1.1
- scipy 1.3.1
- hmmlearn 0.2.3
- graphistry 0.10.4
- plotly 4.5.3
- lxml 4.4.1