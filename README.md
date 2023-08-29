# Financial_Data_Analysis
- 'FINTECH ACADEMY 인공지능 서비스 개발 과정'했던 내용
- 2023학년도 1학기(4학년 1학기) 경희대학교 산업경영공학과 머신러닝 과목에서 했던 프로젝트

# 여행자 보험 데이터 분류
- kaggle : <a href='https://www.kaggle.com/datasets/mhdzahier/travel-insurance?resource=download'> 여행자 보험 데이터</a>
- 1. 데이터 불러오기
- 2. 데이터 전처리(이상치 제거는 하지 않았음)
- 3. 탐색적 자료분석
- 4. 모델링

# 주가 데이터 분석
- yfinance을 활용하여 주가 데이터를 받아옴
- X : 하루 전 종가 데이터
- Y : 당일 종가 데이터
- sklearn 라이브러리를 활용해 X와 Y 관계에 대한 모델을 도출함
- 최종적으로 어제 주가 데이터를 입력하여 오늘의 종가를 예측하는 것을 목표로 함