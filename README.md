# Credit_Risk_Analysis

## Overview
To determine credit card risk, different techniques were employed to train and evaluate models with unbalanced classes. The imbalanced-learn and scikit-learn libraries
are used to build and evaluate the models using resampling. The models are then compared to determine the effectiveness of determining credit risk

## Results
### Naive Random Oversampling
![Naive](https://github.com/Dainita/Credit_Risk_Analysis/blob/main/Naive.jpg)

- Balanced Accuracy Score
  - 0.5656951010512206
- Precision
  - high risk - 0.01
  - low risk - 1.00
- Recall
  - high risk - 0.44
  - low risk - 0.69

### Smote Oversampling
![Smote](https://github.com/Dainita/Credit_Risk_Analysis/blob/main/Smote.jpg)

- Balanced Accuracy Score
  - 0.6397061800254595
- Precision
  - high risk - 0.01
  - low risk - 1.00
- Recall
  - high risk - 0.54
  - low risk - 0.74

### Undersampling
![Under](https://github.com/Dainita/Credit_Risk_Analysis/blob/main/Under.jpg)

- Balanced Accuracy Score
  - 0.6397061800254595
- Precision
  - high risk - 0.01
  - low risk - 1.00
- Recall
  - high risk - 0.53
  - low risk - 0.54

### Combination Over/Under Sampling
![Combination](https://github.com/Dainita/Credit_Risk_Analysis/blob/main/Combination.jpg)

- Balanced Accuracy Score
  - 0.6449163069955265
- Precision
  - high risk - 0.01
  - low risk - 1.00
- Recall
  - high risk - 0.72
  - low risk - 0.57

### Balanced Random Forest Classifier
![Forest](https://github.com/Dainita/Credit_Risk_Analysis/blob/main/Forest.jpg)

- Balanced Accuracy Score
  - 0.7724359911476162
- Precision
  - high risk - 0.03
  - low risk - 1.00
- Recall
  - high risk - 0.66
  - low risk - 0.88

### Easy Ensemble AdaBoost Classifier
![Boost](https://github.com/Dainita/Credit_Risk_Analysis/blob/main/Boost.jpg)

- Balanced Accuracy Score
  - 0.9184747405684778
- Precision
  - high risk - 0.08
  - low risk - 1.00
- Recall
  - high risk - 0.90
  - low risk - 0.93

## Summary
The Easy Ensemble AdaBoost Classifier model performed the best of the models employed to train and evaluate credit card risk. With the high accuracy score, precision and recall (sensitivity), this model would be recommended to predict credit risk. However, credit card companies should consider other methods also as this model leads to a high false positive rate. 

