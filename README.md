# **AIM**
To predict the health risk of pregnant women.

# **DATASET**
Link to the dataset: https://archive.ics.uci.edu/dataset/863/maternal+health+risk
There are 7 columns: Age, Systolic Blood Pressure, Diastolic Blood Pressure, Blood Sugar Level, Body Temperature, Heart Rate and Health Risk.
Health Risk has been classified into 3 risk levels: Low Risk, Mid Risk, High Risk.
<img width="362" alt="image" src="https://github.com/sias01/maternal_health_risk/assets/92619272/77b963d9-28c3-4c0e-b10e-4fe310f59363">

# **PRE PROCESSING**
Remove outliers and perform one-hot encoding on the 'Health Risk' column: Low Risk:0, Mid Risk:1, High Risk:2.

# **MODEL**
Random forest Classifier has been used to perform the task of classification, with the 
It is a supervised learning based model which uses RANDOM FOREST CLASSIFIER in order to make the prediction with an accuracy of 90.19%.

This project is still a work in progress to try implement ANN models in order to improve the accuracy.
