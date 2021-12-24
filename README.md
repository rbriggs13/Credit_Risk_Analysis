# Credit_Risk_Analysis
## Overview
The purpose of this analysis was to determine the best machine learning model to evaluate the data with. Each model's balanced accuracy, precision, and recall scores were determined for six different models.
## Results
### Naive Random Oversampling
- Balanced Accuracy Score: 64.6%
- Precision: 1%
- Recall: 71%
### SMOTE Oversampling
- Balanced Accuracy Score: 65.9% 
- Precision: 1%
- Recall: 63%
### ClusterCentroids Undersampling
- Balanced Accuracy Score: 54.5%
- Precision: 1%
- Recall: 69%
### SMOTEENN Under and Over Sampling
- Balanced Accuracy Score: 66.6%
- Precision: 1%
- Recall: 73%
### Balanced Random Forest Classifier
- Balanced Accuracy Score: 78.9%
- Precision: 3%
- Recall: 70%
### Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Score: 93.1%
- Precision: 9%
- Recall: 92%
## Summary
Looking at all of the models the Easy Ensemble AdaBoost Classifier performed better across the board. Recall is the most import score for this particular model, so while the percision is low the high recall makes the model usable. As a result I would recomend the Easy Ensemble AdaBoost Classifier.
