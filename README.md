# Credit_Risk_Analysis

## Overview:

 The purpose of this analysis is to use machine learning to determine the different levels of accuracy between methods of training and evaluating models as they relate to credit risk.  The models that will be evaluated are:
 - Naive Random Oversampling
 - SMOTE Oversampling
 - Undersampling
 - Combination (Over and Under) Sampling
 - Balanced Random Forest Classifier
 - Easy Ensemble AdaBoost Classifier

## Results:

 The results of each model is listed below:

 Naive Random Oversampling

 ![This is an image](https://github.com/JDBrowder523/Credit_Risk_Analysis/blob/main/Images/Naive_Random_Oversampling.png)
 
 1. The balanced accuracy of this model is 65.47%.
 2. The precision (high_risk/low_risk) of this model is 0.01/1.0.
 3. The recall (high_risk/low_risk) of this model is 0.72/0.59.

 SMOTE Oversampling

 ![This is an image](https://github.com/JDBrowder523/Credit_Risk_Analysis/blob/main/Images/SMOTE_Oversampling.png)

 1. The balanced accuracy of this model is 66.20%.
 2. The precision (high_risk/low_risk) of this model is 0.01/1.0.
 3. The recall (high_risk/low_risk) of this model is 0.63/0.69.

 Undersampling

  ![This is an image](https://github.com/JDBrowder523/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)

 1. The balanced accuracy of this model is 66.20%.
 2. The precision (high_risk/low_risk) of this model is 0.01/1.0.
 3. The recall (high_risk/low_risk) of this model is 0.69/0.40.

 Combination (Over and Under) Sampling
 
 ![This is an image](https://github.com/JDBrowder523/Credit_Risk_Analysis/blob/main/Images/Combination_Sampling.png)

 1. The balanced accuracy of this model is 54.47%.
 2. The precision (high_risk/low_risk) of this model is 0.01/1.0.
 3. The recall (high_risk/low_risk) of this model is 0.72/0.57.

 Balanced Random Forest Classifier

  ![This is an image](https://github.com/JDBrowder523/Credit_Risk_Analysis/blob/main/Images/Balanced_Random_Forest_Classifier.png)

 1. The balanced accuracy of this model is 78.86%.
 2. The precision (high_risk/low_risk) of this model is 0.01/1.0.
 3. The recall (high_risk/low_risk) of this model is 0.70/0.87.

 Easy Ensemble AdaBoost Classifier

  ![This is an image](https://github.com/JDBrowder523/Credit_Risk_Analysis/blob/main/Images/Easy_Ensemble_AdaBoost_Classifier.png)

 1. The balanced accuracy of this model is 93.12%.
 2. The precision (high_risk/low_risk) of this model is 0.09/1.0.
 3. The recall (high_risk/low_risk) of this model is 0.92/0.94.

## Summary:

 The model with the highest balanced accuracy is the Easy Ensemble AdaBoost Classifier model which has an accuracy of 93.12%.  This model also had a precision for high risk that was 3 times higher than the next closest model.  The recall, or sensitivity, for both the high risk and low risk are highest out of all the models with a value above 90%.  Due to the high balanced accuracy and recall, I would recommend that the Easy Ensemble AdaBoost Classifier be used.