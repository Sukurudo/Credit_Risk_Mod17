# Credit Risk Analysis; Low Risk Customers

# Project

Credit risk is an inherently unbalanced classification problem, as the number of good loans easily outnumber the number of risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Your final task is to evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.


#Results

| Model Name | Recall | Precision | Balanced Accuracy Score | 
| ----------- | ------ | --------- | ----------------------- | 
| Random Oversampling | 0.60 | 1.00 | 0.64 |
| SMOTE | 0.72 | 1.00 | 0.65 |
| Undersampling | 0.46 | 1.00 | 0.50 | 
| SMOTEENN | 0.54 | 1.00 | 0.62 | 
| Balanced Random Forest | 0.90 | 1.00 | 0.73 |
| ***Easy Ensemble AdaBoost | 0.95 | 1.00 | 0.91*** |

Based on the various methods used, i would recommend the Easy Ensemble AdaBoost methology. This gives us a accuracy of 91% which is the higest of all options. It also has a recall of 95%, which allows us to have the most low risk applications available to be processed.

Individual analysis of each methology is avaialble within the Jupyter Notebooks.
