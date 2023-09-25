# Seoul Bike Sharing Prediction
## Project description
Currently Rental Bikes are introduced in many urban cities for enhancement of mobility comfort. It is important to make the rental bike available and accesible to the public at right time as it lessens the waiting time. Eventually providing the city with stable supply of rental bikes, becomes a major concern. The crucial part is the prediction of bike count required at each hour for stable supply of rental bikes.

In this project we predict the bike count required at each hour for seoul city, this dataset consists of 8760 rows and 14 columns out of which 4 are categorical and 10 numerical columns, in this dataset there are no duplicates as well null values.
## Problem Statement
Our main agenda is to make rental bike available and accesible to public at right time as it lessens the waiting time, eventually providing city with a stable supply of rental bikes, so our main problem is to predict the bike count required at each hour for stable supply of rental bikes.

Our approach to the problem is to develop different ML models and predict the bike count required at each point of time. We also develop different performance metrics to judge the predicting power of ML models.

## Analysis
In this project we predict the bike count required at each hour for seoul city, this dataset consists of 8760 rows and 14 columns out of which 4 are categorical and 10 numerical columns, in this dataset there are no duplicates as well null values.

First we do a bit of data wrangling to understand our variables better, after that we perform univariate analysis to understand the nature and distribution of our variables, we perform bivariate analysis of our target variable 'Rented bike count' wrt different variables which include categorical and numerical variables, we perform multivariate analysis, we do all these analysis by using various visualization tools.

After throughly analyzing our data, we do hypothesis testing. Based on our understanding of data we develop three hypothetical statements, we do various statistical tests on these statements to verify or reject our claim.

After performing hypothesis testing we now implement various ML models to do prediction, before prediction we must do basic data preprocessing and feature engineering so that our ML models work better.

We do various data preprocessing steps, the first step is handling outliers, second step is feature manipulation and selection, here we perform Variance inflation factor and correlation test to detect multicollinear features and we remove them, after this step we do categorical encoding, i.e we covert our categorical data into numerical types, because of the nature of our data type we have used one hot encoding to do categorical encoding, after this we transform our target variable to make it normal distribution, after this we scale our independent features using standardscalar this is done to get better performance by our models, in final step we split the data into training data and test data in a ratio of 75:25 using train test split. Now our data preprocessing is done and we send the training data and test data to our ML models.

Now we implement various ML models, We have used Linear regression, Ridge regression, Lasso regression, Polynomial regression, Decision trees and Random forest for prediction, for all the models we have done cross validation and hyperparameter tuning using gridsearchcv and we calculated various perfomance metric for each of these models to judge the predicting power of these models, it is found that Random Forest has the best score for our perfomance metric, hence it is the best model among all the models chosen. We also calculate feature importance using random forest to get an idea on which feature is contributing more in deciding the prediction.


