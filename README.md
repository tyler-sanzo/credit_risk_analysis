# credit_risk_analysis

## Overview of Analysis

Using differeng supervised machine learning techniques, we were tasked with creating ML models to determine which credit applications are high-risk. 


### Naive Random Oversampling

- Balanced Accuracy Score: 64.5%
- Precision
  - High risk: 0.01
  - Low risk: 1.00
- Recall
  - High risk: 0.70
  - Low risk: 0.59

### SMOTE Oversampling

- Balanced Accuracy Score: 
- Precision
  - High risk: 0.01
  - Low risk: 1.00
- Recall
  - High risk: 0.63
  - Low risk: 0.69

### Clustered Centroids Undersampling

- Balanced Accuracy Score: 
- Precision
  - High risk: 0.01
  - Low risk: 1.00
- Recall
  - High risk: 0.69
  - Low risk: 0.40

### SMOTEEN Combination Sampling

- Balanced Accuracy Score: 
- Precision
  - High risk: 0.01
  - Low risk: 1.00
- Recall
  - High risk: 0.69
  - Low risk: 0.58

### Balanced Random Forest Classifier

- Balanced Accuracy Score: 
- Precision
  - High risk: 0.03
  - Low risk: 1.00
- Recall
  - High risk: 0.70
  - Low risk: 0.07

### Easy Ensemble Adaptive Boost Classifier**

- Balanced Accuracy Score: 
- Precision
  - High risk: 0.09
  - Low risk: 1.00
- Recall
  - High risk: 0.92
  - Low risk: 0.94

## Summary of Analysis

Looking at the above results, we can see that the high recall model is best for high risk applications to best avoid false negatives ie calling a high risk app low risk.

Because of this, the model which will give best results is the easy ensemble adaptive boost classifier. With a recall of .92, it beats the second closest model by a large margin which had only a recall value of 0.7.
