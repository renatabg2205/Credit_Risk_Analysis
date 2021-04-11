# Credit_Risk_Analysis

## Overview of the analysis
The purpose of this analysis is to evaluate the performance of 6 different machine learning models in order to predict credit risk.

## Results

### 1. Naive Random Oversampling

![Naive Random Oversampling Balanced accuracy score](./Images/NaiveRandomOversampling1.PNG)

![Naive Random Oversampling Risks](./Images/NaiveRandomOversampling2.PNG)

- Balanced accuracy score: 66%

- Precision:
  - High Risk: 1%
  - Low Risk: 100%

- Recall: 
  - High Risk: 66%
  - Low Risk: 67%


### 2. SMOTE Oversampling

![SMOTE Oversampling Balanced accuracy score](./Images/SmoteOversampling1.PNG)

![SMOTE Oversampling Risks](./Images/SmoteOversampling2.PNG)

- Balanced accuracy score: 63%

- Precision:
  - High Risk: 1%
  - Low Risk: 100%

- Recall: 
  - High Risk: 62%
  - Low Risk: 64%

### 3. Undersampling

![Undersampling Balanced accuracy score](./Images/Undersampling1.PNG)

![Undersampling Risks](./Images/Undersampling2.PNG)

- Balanced accuracy score: 53%

- Precision:
  - High Risk: 1%
  - Low Risk: 100%

- Recall: 
  - High Risk: 61%
  - Low Risk: 45%

### 4. Combination (Over and Under) Sampling

![Combination (Over and Under) Sampling Balanced accuracy score](./Images/CombinationSampling1.PNG)

![Combination (Over and Under) Sampling Risks](./Images/CombinationSampling2.PNG)

- Balanced accuracy score: 62%

- Precision:
  - High Risk: 1%
  - Low Risk: 100%

- Recall: 
  - High Risk: 70%
  - Low Risk: 54%

### 5. Balanced Random Forest Classifier

![Balanced Random Forest Classifier Balanced accuracy score](./Images/BalancedRandomForest1.PNG)

![Balanced Random Forest Classifier Risks](./Images/BalancedRandomForest2.PNG)

- Balanced accuracy score: 79%

- Precision:
  - High Risk: 4%
  - Low Risk: 100%

- Recall: 
  - High Risk: 67%
  - Low Risk: 91%

### 6. Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier Balanced accuracy score](./Images/EasyEnsembleAdaBoost1.PNG)

![Easy Ensemble AdaBoost Classifier Risks](./Images/EasyEnsembleAdaBoost2.PNG)

- Balanced accuracy score: 93%

- Precision:
  - High Risk: 7%
  - Low Risk: 100%

- Recall: 
  - High Risk: 0.91
  - Low Risk: 0.94


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)