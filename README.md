# credit-risk-classification

Overview

The purpose of this analysis is to use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. 
After cleaning and splitting the data into X and y training and testing data sets, I created a logistic regression model then fit the model with the original data and resampled data. The data was resampled using RandomOverSampler. 


Results
Machine Learning Model 1:
1.	Precision: 87%
2.	Recall: 89%
3.	Accuracy score: 94.4%
   
Machine Learning Model 2:
1.	Precision: 87%
2.	Recall: 100%
4.	Accuracy score: 99.6%

Summary

The first machine learning model, which was fit with the original data was fairly accurate, with an overall accuracy score of 94.4%. However, some high-risk loans were inaccurately predicted. The second machine learning model, which was fit with the resample data, was much more accurate with a 99.6% accuracy and 100% recall. The precision did not improve from the first model. Nonetheless, I would recommend the company to use the second model as it is nearly perfect at predicting whether the loans are high-risk or healthy. 

