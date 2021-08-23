# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis 

In this project we will use 3 models to predict credit risk 
For oversample we use RandomOverSampler and SMOTE
For undersample we use ClusterCentroids 
For the combination we use SMOTEENN
Also we use two additional models to justify errors. 
They are BalancedRandomForestClassifier and EasyEnsembleClassifier 

## Results 
Naive Random Oversampling 
![image](https://user-images.githubusercontent.com/49871539/130384264-9f21666d-e0b5-4d83-9729-30fa8329c864.png)
high risk precision is 1%  recall score 70%
low risk precision is 100%  recall score 60%
The balanced accuracy score is 65.4%

SMOTE Oversampling 
![image](https://user-images.githubusercontent.com/49871539/130385497-d4f83a58-08aa-4eb7-bc2b-446e86e02161.png)
high risk precision is 1%  recall score 63%
low risk precision is 100%  recall score 69%
The balanced accuracy score is 66.2%

Undersampling 
![image](https://user-images.githubusercontent.com/49871539/130385589-f3541b58-fccc-401c-bdac-452fe4b84a8f.png)
high risk precision is 1%  recall score 69%
low risk precision is 100%  recall score 40%
The balanced accuracy score is 54.4%

Combination Sampling 
![image](https://user-images.githubusercontent.com/49871539/130385699-3c633f50-3542-4ee7-8884-cafa5edbb26c.png)
high risk precision is 1%  recall score 71%
low risk precision is 100%  recall score 57%
The balanced accuracy score is 64.4%

Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/49871539/130385803-329a9ad8-442f-4ef9-8cea-366067cab7db.png)
high risk precision is 4%  recall score 67%
low risk precision is 100%  recall score 91%
The balanced accuracy score is 78.8%

Easy Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/49871539/130385878-69f55630-a8b2-4ed5-a1f3-6bf60e50f485.png)
high risk precision is 7%  recall score 91%
low risk precision is 100%  recall score 94%
The balanced accuracy score is 92.5%

## Summary
The first 4 models has weak precision in high risk case 
the two ensemble models have more sensitivity in high rish case and a little higher precision 
Actually no models is good enough, since the first 4 has low balanced accuracy score and low low risk precision. 
and the last two models has too high recall score. 
if you really need to choose, choose the last 2 models. 





























