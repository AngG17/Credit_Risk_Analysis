# Credit_Risk_Analysis

## Overview

This analysis employed different techniques to train and evaluate models to determine credit risk.  

- Oversample the data using the RandomOverSampler and SMOTE algorithms
- Undersample the data using the ClusterCentroids algorithm
- Combine over and undersamplimg using the SMOTEENN algorithm
- Compare two models that reduce bias, BalancedRandomForestClassifier and EasyEnsembelClassifier

## Results

### RandomOverSampler model

![RandomOverSampler](https://user-images.githubusercontent.com/95720986/164986228-3c1c6277-8f5e-44d6-b41a-3b38846ab6e1.png)

The balanced accuracy score is 62.5%.
The high risk precision is 1% with a 60% sensitivity.
The low risk precision is 100% with a sensitivity of 65%.
Overall, the precision is 99% with a sensitivity of 65%.

### SMOTE model

![SMOTE](https://user-images.githubusercontent.com/95720986/164986497-26307387-b35c-425e-83f9-b0ee7468660e.png)

The balanced accuracy score is 65.1%.
The high risk precision is 1% with a 64% sensitivity.
The low risk precision is 100% with a sensitivity of 66%.
Overall, the precision is 99% with a sensitivity of 66%.

### ClusterCentroids model



## Summary

