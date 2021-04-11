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
  - High Risk: 91%
  - Low Risk: 94%


## Summary

The balanced accuracy scores range from 53% to 93%. The last 2 models (Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier) had the highest scores, 79% and 93% respectively.

These 6 different machine learning models provided a low precision score for high risk credit, ranging from 1% to 7%. Based on these numbers, we can say that a lot of results were false positives and many low risk loans were presented as high risk loans.

All 6 models provided 100% of precision for low risk loans.

The recall values for the first 4 models range from 61%-67% for high risk loans and from 45%-67% for low risk loans. Based on these numbers, we can say that these 4 models are not providing a good enough loan classification prediction.

The recall values for the last 2 models range from 70%-91% for high risk loans and from 91%-94% for low risk loans. These 2 models are providing a better loan classification prediction. 

Based on these results, I would recommed the Easy Ensemble AdaBoost Classifier machine learning model because it provided the most 
