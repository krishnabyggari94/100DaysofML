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

Day 10 -> Selecting the right parameters for a model is very important. There is no one parameter that we can say that it will work for all cases. The right params change for each dataset and as part of Day10, I learned about the RandomizedSearchCV ,GridSearchCV and Hyperopt to tune the hyper parameters. Will continue learning more such methods as part of Day11.

Day 11 -> Finding associations between features is important and it can be done using different methods. As part of Day 11, I learned about CHI Square and T test to check the association between features.

Day 12 -> UnSupervised Learning plays an important role when we don't have a target in the data or when data labelling is a costly affair. As part of Day12, I learned to cluster data using KMeans clustering technique using titanic dataset.

Day 13 -> In UnSupervised Learning, validation of the no of clusters chosen from the elbow method is important. As part of Day13, I learn about the Silhouette validation technique to check how good the data is assigned to different clusters. Also Performed Agglomerative Hierarchial Clustering on the titanic dataset and found that the performance is almost same as that of KMeans clustering. The algos result might vary as the data size increases.

Day 14 -> Understanding the metrics and using the right metrics for a problem statement is important to select the better models. For example, if dataset is imbalanced, accuracy score is not useful and in such cases, confusion matrix/Precision/Recall/f1Score helps in understanding and tuning the model appropriately. Some of the problems require low False Positive and some others might require low False Negatives & based on this, we can fine tune our models. As part of Day 14, I learned more about the Classification metrics and also how to select a better threshold value for binary classification using roc auc curves.

Day15 -> As the no of dimensions of the data increases, the accuracy of the model decreases and data also cannot be visualized. As part of Day15, I learned about the dimensionality reduction techniques like PCA ,TSNE and how to reduce the dimensions and visualize the high dimensional data in 2d and check whether the labels/targets can be separated or not.

Day16 - > The relation between two features helps to understand the data in a better way (like whether they are positively/negatively correlated etc.) As part of Day16, I learned more about the Co Variance, Pearson & Spearman Rank Coefficients and also how to automate basic EDA process using the libraries pandas profiling and sweetviz.

Day17 - > As an ML model cannot understand text data, its important to convert the text into vectors (each word is converted into a vector) and then the ML Algos are applied. In general the no of features for the text data is very high and all the Algos cannot be applied. As part of Day17, I learned more about the basic NLP preprocessing techniques, Stemming, Lemmatization, Bag of words and TF-IDF.
Also , The WPL Challenge by the Widhya.org was really challenging and expecting to learn more better ways of EDA in the coming month.
Dataset used in WPL- https://lnkd.in/ghwr4sT
WPL Challenge Link -https://lnkd.in/gg6SWEQ
GitHub Repo - https://lnkd.in/gGynYzK

Day18 - > As part of Day18, I implemented a simple Multinomial NB algorithm on sample spam sms dataset by vectorizing data using TF-IDF. Also learned about the Word2Vec vectorizing method from gensim library. GitHub Repo - https://lnkd.in/g2NpJjh
Day2 WPL Challenge - https://lnkd.in/gaPCdVd

Day19 - > Often the data which is required for EDA and model building is present in different types of DB and its essential to fetch the required data. And also we can insert our predictions in to a DB after model building for future references and also to check model performance and to improve it further. As part of Day19 , I learned to perform basic CURD operations on Mongo local DB and also how to connect to Mongo cloud DB using Atlas and perform the same operations.

Day20 - > As part of Day20, I learned how to automate basic data preprocessing and create models using the open source library PyCaret which automates most of tasks(from processing, model building to deployment). Top best models can be selected as per the required metrics and can be fine tuned to improve the model.
GitHub Repo - https://lnkd.in/gR-zHzp

Day21 - > For simple Datasets most of the times basic ML models perform well. But as the complexity increases, boosting and bagging algorithms tend to perform better. As part of Day21, I learned how to use different boosting algorithms like XgBoost, Lightgbm, Catboost on sample diabetes dataset.
GitHub Repo - https://lnkd.in/gdBuFfh

Day22 - > As part of Day22 , I performed basic EDA on the house price prediction dataset and would do further analysis and explore the data in a better way in the coming days. 
GitHub Repo - https://github.com/krishnabyggari94/house-price-prediction

Day23 - > As part of Day 22, I continued the house price prediction project and implemented data preprocessing, feature engineering and hyper parameter tuned different models and found SVR regressor and GradientBoostingRegressor performed better than other models till now with r2_score ~0.91 and root mean square log error ~0.14 . Will continue further to build better features and better models.
GitHub Repo - https://lnkd.in/gEJmwjS

Day24 - > If the data is very huge, after some extent, the ML Algos accuracy cannot be increased and in such scenarios by using DL we can achieve better accuracies. Perceptron is a single layer neural network which is the base for all the Deep Learning algorithms . As part of Day24, I learned about Perceptron and how it is implemented.

Day25 - > I started practicing on the dataset 'Predicting the no of likes of videos' and performed the basic EDA like which channels published more videos, which countries videos got the highest no of likes, which channel videos got more likes, on which days more videos are published, which words in the Title/Description got more likes etc..
GitHub Repo - https://lnkd.in/gfCJKbH
Dataset Link - https://lnkd.in/gjzvvHm

Day26 - > Data Preprocessing is an important step in ML and As part of Day26, I performed the basic data processing on the 'likes prediction on videos' data & built a simple RandomForest Regressor which has shown an error less than that of other models like KNeighbors , Linear Regression etc. By tuning the hyper params, we can get a better model.
