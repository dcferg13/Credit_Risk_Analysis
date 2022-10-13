# Credit_Risk_Analysis
evaluate three machine learning models by using resampling to determine which is better at predicting credit risk.
## Overview
The purpose of this analysis is to compare the use of different models of machine learning to see which of these models would be best suited, if any, to predict credit risk. These models include, the RandomOverSamper, SMOTE, ClusterCentroids, SMOTEEN, BalancedRandomForestClassifier and EasyEnsembleClassifier.
## Results
Below is the following results of the models used:

### RandomOverSampler

![naive_random_oversampling](https://user-images.githubusercontent.com/107289345/195694783-7ef9bfce-de73-41b4-9771-97a0b5ac3f51.png)

- Balanced Accuracy Score: 64%
- Precision HighRisk: 0.01
- Pecision LowRisk: 1
- Recall HighRisk: 0.69
- Recall LowRisk: 0.59

### SMOTE

![smote](https://user-images.githubusercontent.com/107289345/195696184-1b94cd73-eec2-4507-967f-002d63407279.png)

- Balanced Accuracy Score: 66%
- Precision HighRisk: 0.01
- Precision LowRisk: 1
- Recall HighRisk: 0.63
- Recall LowRisk: 0.69

### ClusterCentroids

![cluster_centroids](https://user-images.githubusercontent.com/107289345/195697035-65bd5f68-5366-4ea1-8d38-bdea01081814.png)

- Balanced Accuracy Score: 54%
- Precision HighRisk: 0.01
- Precision LowRisk: 1
- Recall HighRisk: 0.69
- Recall LowRisk: 0.40

### SMOTEEN

![smoteen](https://user-images.githubusercontent.com/107289345/195696892-31223eaf-1b33-4660-b09c-488da8418369.png)

- Balanced Accuracy Score: 54%
- Precision HighRisk: 0.01
- Precision LowRisk: 1
- Recall HighRisk: 0.69
- Recall LowRisk: 0.59

### BalancedRandomForestClassifier

![blanced_random_forest_classifier](https://user-images.githubusercontent.com/107289345/195696935-785e1fa8-8aaf-428c-93b9-59f41aa77220.png)

- Balanced Accuracy Score: 79%
- Precision HighRisk: 0.03
- Precision LowRisk: 1
- Recall HighRisk: 0.70
- Recall LowRisk: 0.87

### EasyEnsembleClassifier

![easy_ensemble_classifier](https://user-images.githubusercontent.com/107289345/195697116-0b83186a-cea3-4d5e-b33a-6fb366b93c28.png)

- Balanced Accuracy Score: 93%
- Precision HighRisk: 0.09
- Precision LowRisk: 1
- Recall HighRisk: 0.92
- Recall LowRisk: 0.94

 

## Summary
