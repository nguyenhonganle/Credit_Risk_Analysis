# Credit_Risk_Analysis

## Table of Contents

- [Overview of Project](#overview-of-project)
- [Results](#results)
- [Summary](#summary)

### Overview of Project

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use `imbalanced-learn` and `scikit-learn` libraries to build and evaluate models using resampling.

### Results

+ Naive Random Oversampling results: Our balanced accuracy test it 67%, the precision for the high_risk has a very low positivity at 1% and the recall is 74%

+ SMOTE oversampling results: the accuracy score is 66.2%, the precision for the high_risk loans has a low positvity again at 1% and recall is 69% overall

+ Undersampling results: balanced accuracy score is 66.2% overall, the precision is at 99% and the recall is 41%

+ Combination(over and undersampling) results: balanced accuracy score is 54.7% the precision is 99% and the recall is 57% overall

+ Balanced Random Forest Classifier results: the accuracy score is 77.2% the precision is 99% and the recall is 88%

+ Easy Ensemble AdaBoost Classifier results: the accuracy score is 91.7% the precision is 99% and the recall is 94%

### Summary

- For all models, utlizing **EasyEnsembleClassifier** is the most effective. Provides a highest Score for all Risk loans.

- The precision is low or none for all the models. In General, above the 90% of the current analysis, utlizing **EasyEnsembleClassifier** will perform a High-Risk loan precision as a great value for the overall analysis. 

