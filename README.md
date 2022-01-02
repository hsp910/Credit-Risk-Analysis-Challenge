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

In industries such as the financial industry, sensitivity is more valuable than precision when analyzing risk and default rates on loan candidates. This is primarily because banks would use this sort of technology to flag primarily high risk candidates as high risk. Therefore already reducing the default rate they currently have.

On the topic of precision, the precision for high risk candidates was incredibly low for all the models. The highest the precision got was 7% for the Easy Ensemble Classifier tests, and this is obviously still a very poor outcome in terms of precision. To be more precise, the machine learning algorithm was only able to identify roughly 7% of all high risk candidadtes within the data set it was provided for testing. Though for what it is worth, every single model was able to predict low risk individuals with perfect precsiion from the data set.

Back on the topic of sensitivity, which is labeled as recall or 'rec' in the screenshots and tables above, there is a generally higher outcome for these algorithms. The highest recall found in the algorithms was 91% which was found in the Easy Ensemble Classifier algorithm as well. The next two highest recalls were the SMOTEENN Combination Sampling and the Balanced Random Forest Classifier  with 70% and 67% recall respectively.

The final topic to tackle will be the balanced accuracy score of the models. This will likely be the determining factor on which model to use for the future. The accuracy score is used to show how correct the model was. This means the higher the score, the larger precentage of correct predictions the model made on the classifications of individuals in the datasets they were provided. From the table above we can see that once more, the Easy Ensemble Classifier has the highest balanced accuracy score of all the models. With this model proving to have the highest precision, highest sensitivity, and the highest accuracy it only seems reasonable to choose this as the basis for our future analysis and models. 
