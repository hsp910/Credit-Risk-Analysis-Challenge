# Credit Risk Analysis Challenge

*Data set for this analysis not included due to github file size constraints*

## Overview 

The purpose of this challenge is to use different machine learning models to analyze credit risk to provide a quicker and more reliable loan experience for end users. From this we chose 6 different machine learning models to test on their accuracy and reliability. Doing so would allow us to help find good candidates for loans which would lead to a financial institutions, such as a bank, being able to reduce their default rate on loans they give out. The six machine learning models chosen were and tested with Python's imbalanced-learn and scikit-learn libraries. 

## Results

|ML Model|Balanced Accuracy Score|Precision|Recall|F1|
|----|----|----|----|----|
|Naive Random Oversampling|0.63|0.99|0.68|0.81|
|SMOTE Oversampling|0.63|0.99|0.63|0.77|
|Cluster Centroids Undersampling|0.53|0.99|0.45|0.62|
|SMOTEENN Combination Sampling|0.64|0.99|0.58|0.73|
|Balanced Random Forest Classifier|0.79|0.99|0.91|0.95|
|Easy Ensemble Classifier|0.93|0.99|0.94|0.97|

Screenshots of the actual code ran supplied below.

### Naive Random Oversampling

![NRO](https://i.imgur.com/BJYZxdv.png)

### SMOTE Oversampling

![SMOTE](https://i.imgur.com/ojqPIOI.png)

### Cluster Centroids Undersampling

![CCU](https://i.imgur.com/EPXT12E.png)

### SMOTEEEN Combination Sampling

![SMOTEENN](https://i.imgur.com/n7CCYwd.png)

### Balanced Random Forest Classifier 

![BRFC](https://i.imgur.com/mc3BMl4.png)

### Easy Ensemble Classifier

![EEC](https://i.imgur.com/8meXq9J.png)

## Summary

