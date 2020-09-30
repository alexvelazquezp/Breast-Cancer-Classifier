# Breast Cancer Classifier
Using a dataset with more than 500 previous samples, in this notebook we are going to build a model for the detection of breast cancer. To achieve the most efficient model, we are going to analyze 4 different models based on logistic regression, K-Nearest neighbor, decision trees and support vector machines. Finally, we will compare its performance and accuracy.

As can be seen in the notebook, and as detailed in the following table, logistic regression was the optimal model:

Model | Accuracy (%) | AUC | False negatives | False positives | Fit time (s) | Prediction time (s)
----- | ------------ | --- | --------------- | --------------- | ------------ | -------------------
Logistic Regression | 98.25 | 0.976 | 2 | 0 | 0.003 | 0.001
KNN K-Nearest Neighbor | 95.61 | 0.940 | 5 | 0 | 0.003 | 0.007
Decision Trees | 95.61 | 0.940 | 5 | 0 | 0.007 | 0.001
SVM Support Vector Machines | 97.37 | 0.969 | 2 | 1 | 0.004 | 0.001
