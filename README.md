# NYC-Taxi-Trip-Duration

Problem Statement: Given a dataset with various attributes, develop a model that predicts the trip duration of any given taxi ride in New York City.

The Drive link for the dataset has been provided in the file dataset link.txt.

I have used 3 notebooks as a part of the solution:

1. NYC Taxi Trip Duration EDA.ipynb: Exploratory Data Analysis for determining what are the factors affecting the trip duration and how they influence it.  

2. NYC Trip - Linear Models Final.ipynb: Checking whether the assumptions of linear regression are satisifed for our dataset. This is done to check if linear regression can be applied to the dataset or not, and whether transforming the data can help. Refer this blog for more details on how this works: https://www.analyticsvidhya.com/blog/2016/07/deeper-regression-analysis-assumptions-plots-solutions/ 

3. NYC Trip Duration.ipynb: Even if we can use Linear Regression on the dataset, it might not be the best one to use. Here, we check how some other models perform on the dataset and tasks such as data pre-processing, feature engineering, modelling, ensembling and hyperparameter tuning have also been taken care of.
