# beauty sales prediction

## 0. requirements

graphviz 2.38  
jupyter 1.0.0  
matplotlib 3.3.4  
notebook 6.3.0  
numpy 1.20.1  
pandas 1.2.4  
python-graphviz 0.16  
python 3.9.4  
scikit-learn 0.24.1  
anaconda 3

## 1. data collection

    매출액에 대한 관심 -> 서울시 열린 데이터 광장 -> 미용업계 매출액 예측 타게팅

    서울시 우리마을가게 상권분석서비스(.csv) data collection

## 2. data analysis & preprocessing

    features (17개) - one hot encoding(quarter, business_area, business), 매출건수 비율(주중, 남성, 여성, 낮, 밤)

    불필요한 data rows, columns drop

    histogram, scatter matrix
   
    normalization
   
    점포수 0 data를 1로 변경
   
    여러 점포수 매출 합 -> 점포 하나당 매출
   
    매출이 너무 큰 점포 데이터 삭제

    data split - train data, test data
    
## 3. datasets

    train - 10922 rows, 17 columns
    
    test - 2731 rows, 17 columns

## 4. model selection & training

    linear regression

    decision tree regressor

    random forest regressor

## 5. grid search, randomized search

    random forest
