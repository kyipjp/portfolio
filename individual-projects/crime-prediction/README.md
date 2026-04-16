# Crime Prediction Project

Setup AWS EMR cluster with Spark, then, do a machine learning experiment with
dataset provided. Training dataset and test dataset can be downloaded from Moodle. (The dataset
is derived from https://data.sfgov.org/)

## Instructions
Spark framework is very useful in machine learning field because of the bigger and bigger dataset.
And using Python with pyspark library can help you write a machine learning program under spark
framework easily. In this assignment, you are required to write a machine learning program to
classify samples using library pyspark.

The task is to classify Crime Description into 30 pre-defined categories. Given a new crime
description, you are required to assign it to one of the categories. We assume that each crime
description is assigned to one and only one category.

Explanation of the data fields is as follows:
1. Date: timestamp of the crime incident
2. Category: category of the crime incident. (This is the target variable you are going to
predict)
3. Description: detailed description of the crime incident
4. DayOfWeek: the day of the week
5. PdDistrict: name of the Police Department District
6. Resolution - how the crime incident was resolved
7. Address - the approximate street address of the crime incident ( “/” means intersection
of two roads)
8. X - Longitude
9. Y - Latitude
Note:
• The dataset has gone through some basic data cleaning (Filter out NA values, Remove
Imbalanced Data)
• The list of the 30 categories is in the appendix for your reference.

There are many ways to handle this problem, clustering algorithms, logistic regression algorithms,
Support Vector Machines, or using artificial neural networks. You should try AT LEAST ONE
algorithm to solve the problem.
