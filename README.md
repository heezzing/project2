Project2 : 국가별 국방비 예측 모델

1.   데이터 선정 이유 및 문제 정의*
   -   선정 이유 : 우크라이나와 러시아의 전쟁을 보며 내가 누리고있는 안전은 언제든지 없어질수 있다고 느꼈다. 나라별로 국가를 지키기위해 국방비에 투자하는 규모가 궁금해져서 데이터를 선정하게 되었다.

   -   군사비의 규모를 예측하기 위해 회귀 문제로 접근하고자 함.

2. 데이터를 이용한 가설 및 평가지표, 베이스라인 선택*  
  - 가설 : gdp대비 국방비 비율과 국가지출 대비 국방비 비율이 국방비의 규모에 크게 영향을 미치고 있다.

  - 예측하고자 하는 변수

    - target : 국방비(M_USD)
    - feature : M_of_gov,M_of_GDP

  - 그 이유 : 국방비를 보면 그 군대의 규모를 알 수 있어서.

  - 베이스라인 모델

    - 단순선형회귀모델.

    - 이유 : 국방비 규모라 분류보단 회귀가 맞다고 생각하여 회귀를 선택함.


  - 평가지표 선택

    - 회귀 평가지표(evaluation metrics): MAE,MSE,RMSE,R^2

3. 데이터 출처

    - Kaggle : https://www.kaggle.com/datasets/prasertk/military-expenditure-by-country-from-19702020  

4. 발표영상 링크

      - https://youtu.be/zvVHcPlQEOk
