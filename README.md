# Credit_Risk_Analysis
## Overview
The purpose of this analysis was to determine the best machine learning model to evaluate the data with. Thus, each model's balanced accuracy, precision, and recall scores were determined for six different models.
## Results
Random Oversampling:
  -Balanced Accuracy Score: 64.6%
  -Precision: 1%
  -Recall: 71%
  
SMOTE Oversampling:
  -Balanced Accuracy Score: 65.9%
  -Precision: 1%
  -Recall: 63%
  
ClusterCentroids Undersampling:
  -Balanced Accuracy Score: 54.5%
  -Precision: 1%
  -Recall: 69%
  
SMOTEENN Under and Over Sampling:
  -Balanced Accuracy Score: 66.6%
  -Precision: 1%
  -Recall: 73%
  
Balanced Random Forest Classifier:
  -Balanced Accuracy Score: 78.9%
  -Precision: 3%
  -Recall: 70%
  
Easy Ensemble AdaBoost Classifier:
  -Balanced Accuracy Score: 93.1%
  -Precision: 9%
  -Recall: 92%
  
  ## Summary
Lower accruacy were encountered in Naive Random Oversampling, SMOTE Oversampling, Undersampling, and Combination (Over and Under) Sampling.
While these approached yielded over 90% accruacy Balanced Random Forest Classifier, Easy Ensemble AdaBoost Classifier.
I would recommend more work be done to see if their results would improve with better training and testing.
