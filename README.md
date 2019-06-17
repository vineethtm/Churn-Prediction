# DSND-Capstone
## Predict the Churn 

### Introduction
The dataset consists of transactions of a number of users on a music platform. Some of these users will eventually cancel their subscription. My aim is to predict those who will churn. This project is also an opportunity to learn and use Spark in a real world project

### Data
Total Number of rows : 286500 \
Column names are: \
artist,auth,firstName,gender,itemInSessionlastName,length,level,location,method,page,registration,sessionId,song,
status,ts,userAgent,userId \
Total Number of Unique users are 226 

### Tools used
Pyspark,Spark SQL, Matplotlib

### Techniques Used
1. Data Cleaning 
2. Feature Engineering 
3. Model Building 

### Machine Learning Techniques used
1. Logistic Regression 
2. Linear SVC 
3. Random Forests
4. Cross Validation and Parameter Grid Search

### Perfomance
Metric used is f1-score \
f1-score on the Training set : 0.68 \
f1-score on the Test set : 0.646
