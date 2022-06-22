# Credit_Risk_Analysis

## Overview of the Analysis

Creidt card credit data from 2019 Q1 was analyzed to predict credit risk by evaluating various models using resampling. Techniques were performed such as oversampling  using the RandomOverSampler and SMOTE algorithms, undersampling using the ClusterCentroids algorithm, a combinatorial approach using the SMOTEENN algorithm, and utlizing two machine learning models: BalancedRandomForestClassifier and EasyEnsembleClassifier. 


## Results

The following balanced accuracy, precision, and recall scores of all six machine learning models were identified:
#### Naive Random Oversampling using RandomOverSampler
* balanced accuracy score: 0.6366972052004142
* precision (high, low): 0.01, 1.00 
* recall (high, low): 0.62, 0.65
#### SMOTE Oversampling 
* balanced accuracy score: 0.6302712208564487
* precision (high, low): 0.01, 1.00 
* recall (high, low): 0.62, 0.64
#### Undersampling using ClusterCentroids
* balanced accuracy score: 0.5293318990697431
* precision (high, low): 0.01, 1.00 
* recall (high, low): 0.61, 0.45           
#### Combination using SMOTEENN
* balanced accuracy score: 0.5293318990697431
* precision (high, low) : 0.01, 1.00
* recall (high, low): 0.70, 0.57
#### Undersampling using ClusterCentroids
* balanced accuracy score: 0.5293318990697431
* precision (high, low):
* recall (high, low):
#### BalancedRandomForestClassifier
* balanced accuracy score: 0.7877672625306695
* precision (high, low): 0.04, 1.00
* recall (high, low): 0.67, 0.91           
#### EasyEnsembleClassifier
* balanced accuracy score: 0.925427358175101
* precision (high, low): 0.07, 1.00
* recall (high, low): 0.91, 0.94
## Summary

