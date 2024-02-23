#  Boston House Prices 🏠

## Type of problem : Regression problem 

## Dataset Description: 
- The dataset is often used to train regression models to predict the median value of homes based on some related features


## The proposed framework is summarized in the following steps:
The proposed framework is summarized in the following steps:

1- Data exploration 🔎 : Check the number of features and rows, missing values, duplicate values and generating descriptive statistics for this data 

2- Data visualization 📊 : 
* use histplot from Seaborn library to see the distribution of data for each feature and try to reach insight from it.
* comparing each feature with the dependent feature and try to reach insight from it.
* Checking if there is high correlation between each attributes.

3- Data preprocessing 🛠 : Data Splitting ,Data Cleaning (Handling Missing Values & Outliers Values), Handling Imbalanced Data (Oversampling), Scaling by Standard Scaler

4- Selecting and comparing models 🎯 : After many experiments and attempts with most of the famous models in classification problems, I found Three Models give me High performance (ExtraTreesRegressor, XGBRegressor, RandomForestRegressor). 

5- Fine tuning 🪄 : I used Optuna (optimization framework for machine learning models) to choose the best hyperparameters for Three Models.

8- Ensemble Model 📈: I used Voting Regressor between this Models to improve overall performance and generalization.

6- Evaluation using test set ⚖ 

7- Saving model 🗃

