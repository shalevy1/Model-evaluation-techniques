# Data prepocessing

The code in the jupyter notebook follows the hands-on analysis from the book Data Mining and Predictive Analytics by Larose & Larose, Part III, Chapter 15.

## Data set

The dataset (**churn.txt**) used in the notebook could be downloaded from the repository.

## Python version

Python 2

## Terminology

False-positive rate = FP/FP+TN  
False-negative rate = FN/FN+TP

Proportion of true positives = TP/TP+FP  
Proportion of true negatives = TN/FN+TN  
Proportion of false positives = 1-PTP = FP/FP+TP  
Proportion of false negatives = 1-PTN = FN/FN+TN  

Accuracy = TP+TN/TP+FP+FN+TN - the ratio of correctly predicted observations to the total observations  
Overall error rate 1-Accuracy = FN+FP/TP+FP+FN+TN = the ration of incorrectly predicted observations to the total number  
Precision = TP/TP+FP - the ratio of correctly predicted positive observations to the total predicted positives  

Sensitivity/Recall = TP/TP+FN - the ratio of correctly predicted positive observations to the all observations in actual class  
Specificity = TN/FP+TN - the ration of correctly predicted negative observation to the total predicted negatives   

F1 Score = 2*(Recall * Precision) / (Recall + Precision)
