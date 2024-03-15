# Deep_learning_DataAnalysis
 머신러닝 데이터분석

# 240315머신러닝_와인_분석.ipynb
## sklean의 wine 데이터를 이용하여 class = 1 레드와인 class = 0 화이트 와인을 분류     
catboost, lightbgm, xgboost 등을 이용하여 학습을 진행하였고 feature importance 순위를 추출하여 사후 분석을 진행 하였다    
wine = pd.read_csv('./wine.csv') 일때    
red_wine = wine[wine['class']==1]    
red_wine.describe()    

white_wine = wine[wine['class']==0]    
white_wine.describe()    
으로 두 클래스 간의 feature importance 값을 비교한다.    
