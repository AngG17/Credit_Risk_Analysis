# Credit_Risk_Analysis

## Overview

This analysis employed different techniques to train and evaluate models to determine credit risk.  

- Oversample the data using the RandomOverSampler and SMOTE algorithms
- Undersample the data using the ClusterCentroids algorithm
- Combine over and undersamplimg using the SMOTEENN algorithm
- Compare two models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier

## Results

### RandomOverSampler model

![RandomOverSampler](https://user-images.githubusercontent.com/95720986/164986228-3c1c6277-8f5e-44d6-b41a-3b38846ab6e1.png)

- The balanced accuracy score is 62.5%.
- The high risk precision is 1% with a 60% sensitivity and an F1 score of 2%.
- The low risk precision is 100% with a sensitivity of 65%.
- Overall, the precision is 99% with a sensitivity of 65% and an F1 score of 78%.

### SMOTE model

![SMOTE](https://user-images.githubusercontent.com/95720986/164986497-26307387-b35c-425e-83f9-b0ee7468660e.png)

- The balanced accuracy score is 65.1%.
- The high risk precision is 1% with a 64% sensitivity and an F1 score of 2%.
- The low risk precision is 100% with a sensitivity of 66%.
- Overall, the precision is 99% with a sensitivity of 66% and an F1 score of 79%.

### ClusterCentroids model

![ClusterCentroids](https://user-images.githubusercontent.com/95720986/164986683-efb257e9-fa5c-4bbb-8de5-004653f0c86b.png)

- The balanced accuracy score is 65.1%.
- The high risk precision is 1% with a 60% sensitivity and an F1 score of 1%.
- The low risk precision is 100% with a sensitivity of 43%.
- Overall, the precision is 99% with a sensitivity of 44% and an F1 score of 60%.

### SMOTEENN model

![SMOTEENN](https://user-images.githubusercontent.com/95720986/164986856-e5ed967d-bab1-4e60-a916-d3dbc048415a.png)

- The balanced accuracy score is 51.6%.
- The high risk precision is 1% with a 70% sensitivity and an F1 score of 2%.
- The low risk precision is 100% with a sensitivity of 57%.
- Overall, the precision is 99% with a sensitivity of 57% and an F1 score of 72%.

### BalancedRandomForestClassifier model

![BalancedRandomForestClassifier](https://user-images.githubusercontent.com/95720986/164986994-6df18720-7b71-420f-9975-83892541c4ae.png)

- The balanced accuracy score is 80.5%.
- The high risk precision is 4% with a 73% sensitivity and an F1 score of 7%.
- The low risk precision is 100% with a sensitivity of 88%.
- Overall, the precision is 99% with a sensitivity of 88% and an F1 score of 93%.

### EasyEnsembleClassifier model

![EasyEnsembleClassifier](https://user-images.githubusercontent.com/95720986/164987124-d7d25640-feaa-40f6-93d0-24118530c34a.png)

- The balanced accuracy score is 91.8%.
- The high risk precision is 9% with a 89% sensitivity and an F1 score of 16%.
- The low risk precision is 100% with a sensitivity of 94%.
- Overall, the precision is 99% with a sensitivity of 94% and an F1 score of 96%.

## Summary

The ability of any of these models to predict high risk with any amount of precision is quite low.  I would not recommend using any of these models to predict credit risk.
