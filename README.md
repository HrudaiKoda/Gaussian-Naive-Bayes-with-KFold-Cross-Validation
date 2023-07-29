# Gaussian-Naive-Bayes-with-KFold-Cross-Validation

## Overview
- Fetal Health data is available in dataset classified into 3 different classes ( Normal , Suspect , Pathological )
- The dataset has 21 features for each observation.
- Segregated the available dataset into 80% as Training data and remaining 20% as Testing dataset.
- Selected best 11 features using SelectKBest which utilized F-score comparison ( Anova Feature Selection ).
- Normalized the features and incorporated KFold Cross Validation and did some trial & error runs for various K values and figured out K=5 had optimal results.
- By utilized all these methods the accuracy of the model has increased from 75% to 84%.
