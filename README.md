# supervised learning

1. data collection

   매출액에 대한 관심 -> 서울시 열린 데이터 광장 -> 미용업계 매출액 예측 타게팅

   서울시 우리마을가게 상권분석서비스(.csv) data 수집

2. data analysis & preprocessing

   data feature

   quarter, business_area, business (one hot encoding)

   주중 매출건수 비율, 남성 매출건수 비율, 여성 매출건수 비율, 낮 매출건수 비율, 밤 매출건수 비율, 점포수

   불필요한 data rows, columns drop

   scatter matrix
   
   점포수 0 data를 1로 변경
   
   여러 점포수 매출 합 -> 점포 하나당 매출
   
   매출이 너무 큰 점포 데이터 삭제
   
   normalization

   data split - train data, test data

3. model sellection & training

   linear regression

   decision tree regressor

   random forest regressor

4. grid search, randomized search

   random forest로 선정
