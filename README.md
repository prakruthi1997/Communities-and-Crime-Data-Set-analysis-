# Communities-and-Crime-Data-Set-analysis-
This dataset (dimension 1994 x 128) combines law enforcement data from the 1990 US LEMAS survey, socio-economic data from the 1990 US Census and crime data from the 1995 FBI UCR
1.  Data Preparation: Start with the data set crime.csv. 
Below are some minor data preparation and exploration activities.
1. Remove those columns from the data that are not useful for prediction. 
2. Look at the missing percentage of each remaining variable. Remove those variables that have data missing percent of more than 60%. 
3. Impute or replace the remaining missing values appropriately. 
4. Conduct some Exploratory Data Analysis. 
Check the distribution of the target variable ViolentCrimesPerPop. 
 
2. Partitioning Data: Randomly partition your data into two sets: the training set D1 and the test set D2 with a ratio of 2:1.  
 
3. Predictive Modeling: I've fitted seven models  from the following models using the training set D1: 
1. Linear regression with stepwise selection. 
2. LASSO or SCAD  
3. Ridge Regression (RR) 
4.Gradient boosting with hyper-parameter tuning.
5. Partial least squares regression (PLSR)  
6. Stagewise regression 
7. Least angle regression (LAR)
d
And I've calculated the r2 score for each model along with the MSE and taken the best model for consideration
