# NYC-Taxi-Trip-Duration

Problem Statement: Given a dataset with various attributes, develop a model that predicts the trip duration of any given taxi ride in New York City.

The Drive link for the dataset has been provided in the file dataset link.txt.

Below is the description of some dataset attributes:

1. id - a unique identifier for each trip
2. vendor_id - a code indicating the provider associated with the trip record
3. pickup_datetime - date and time when the meter was engaged
4. dropoff_datetime - date and time when the meter was disengaged
5. passenger_count - the number of passengers in the vehicle (driver entered value)
6. pickup_longitude - the longitude where the meter was engaged
7. pickup_latitude - the latitude where the meter was engaged
8. dropoff_longitude - the longitude where the meter was disengaged
9. dropoff_latitude - the latitude where the meter was disengaged
10. store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the 11. server (Y=store and forward; N=not a store and forward trip)
12. trip_duration - (target) duration of the trip in seconds


I have used 3 notebooks as a part of the solution:

1. NYC Taxi Trip Duration EDA.ipynb: Exploratory Data Analysis for determining what are the factors affecting the trip duration and how they influence it.  

2. NYC Trip - Linear Models Final.ipynb: Checking whether the assumptions of linear regression are satisifed for our dataset. This is done to check if linear regression can be applied to the dataset or not, and whether transforming the data can help. Refer this blog for more details on how this works: https://www.analyticsvidhya.com/blog/2016/07/deeper-regression-analysis-assumptions-plots-solutions/ 

3. NYC Trip Duration.ipynb: Even if we can use Linear Regression on the dataset, it might not be the best one to use. Here, we check how some other models perform on the dataset and tasks such as data pre-processing, feature engineering, modelling, ensembling and hyperparameter tuning have also been taken care of.
