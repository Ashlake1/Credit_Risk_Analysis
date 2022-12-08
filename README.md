# Credit_Risk_Analysis

## Overview of Analysis 
In this analysis we are using different techniques to train and evaluate data within an unbalanced class in order to assess credit risk. 

### The Techniques Employed: 
- Use Resampling Models to Predict Credit Risk
- Use the SMOTEENN Algorithm to Predict Credit Risk
- Use Ensemble Classifiers to Predict Credit Risk

## Results
- Naive Random Oversampling results:
![Naive_Random_Oversampling.png](/Resources/Naive_Random_Oversampling.png)

- SMOTE Oversampling Results:
![SMOTE_Oversampling_Results.png](/Resources/SMOTE_Oversampling_Results.png)

- Undersampling Results:
![Undersampling_Results.png](/Resources/Undersampling_Results.png)

- Combination (Over and Under) Results:
![Combination_Results.png](/Resources/Combination_Results.png)

- Balanced Random Forest Classifier results:
![brfc_results.png](/Resources/brfc_results.png)

- Easy Ensemble AdaBoost Classifier Results:
![eeab_results.png](/Resources/eeab_results.png)

## Summary
Easy Ensemble performed the best and provided the most accurate results - over 91% with a precision of 99%. The oversampling algorithms were about 30% less accurate than than Easy Ensemble however undersampling by far had the worst results. I would recommend using the Easy Ensemble method. 