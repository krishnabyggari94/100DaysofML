# 100DaysofML

Day 1 -> Applied a Simple Linear Regression model on the dataset and found the r2_score to be 0.81 and made a webapp using Flask , deployed it in Heroku.  
Day 2 -> Applied a Lasso,Ridge,ElasticNet models on the dataset and found the r2_score is almost similar to that of Simple Linear Regression.  
Day 3 -> Participated in the Hacklive guided community Hackathon by Analytics Vidhya - https://datahack.analyticsvidhya.com/contest/hacklive-guided-community-hackathon   
Day 4 -> Performed basic Feature enginerring techniques on cross-sell-prediction dataset - https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction  
Day 5 -> Feature scaling is very important as each and every feature might be of different unit like height in cms/mts/feet etc. If features are not scaled properly, the overall model will be useless. Data doesn't always come clean. Most of the times it has missing values and they must be handled without which the features might loose their predictive power. As part of Day 5 I have used MinMaxScaler, StandardScaler, RobustScaler for scaling the features and also performed different imputation techniques on the missing numerical features (like mean/median/Mode replacement, Arbitrary imputation, random sample imputation, new column imputation of nan etc.) All these are performed on the titanic and house price prediction datasets from kaggle. datasets - https://www.kaggle.com/c/house-prices-advanced-regression-techniques , https://www.kaggle.com/c/titanic        

Day 6 -> If Datetime is a feature of data, then it might be one of important feature that tells a lot about target. For example, if dataset is of sales and order date is present in it , then encoding new features like week_day(sunday,monday etc..), month, hour etc. There might be patterns in this new features like the sales is more on weekends or sales is high during a particular hours of the day etc. By using these features the model can predict the sales in a better way. 
Today I learned more about encoding such datetime features, target ordinal , target mean, probability ratio encodings using simple datasets from kaggle like titanic, house price prediction and store sales datasets.    

Day 7 -> Often the datasets are imbalanced and based on that we have to select suitable modelling technique. Accuracy is not best metric for such datasets. Suppose if a dataset has 100 points and only 2 belongs to class 1 , remaining belongs to class 2, and if we predict all values as class 1, we have 98% accuracy and such models are dumb and are of no value. As part of Day 7, I learned how to handle imbalanced dataset, which algos can overcome this issue, under sampling, oversampling and smote technique and how we can make better data to train.  Dataset link - https://www.kaggle.com/mlg-ulb/creditcardfraud   

Day 8 -> Outliers are quite common in the data . All outliers are not bad and some are useful for better prediction/improving model performance. For example, if heart beat is a feature in dataset , the irregularities in it might give some info about some disease/problem and help the model to improve in predicting diseases. As part of Day 8, I learned about the outlier detection techniques both in gaussian & skewed distributions using titanic dataset and also how to fix them using 3-std, IQR technique and how we can adjust the range based on data.      

Day 9 -> Selecting the right features for a model is important to perform better. Even if the data has hundreds of fearures, few features (like 15-20) can contribute more for the model performance. As part of Day 9, I learned how to select better features using Correlation, ExtraTreeClassifiers, SelectKBest and Information Gain.



