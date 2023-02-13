## A MACHINE LEARNING MODEL WHCH PREDICTS THE CHANCES OF PATIENTS' SURVIVAL AFTER THE SINGULAR NEXT CALENDER YEAR OF MEDICAL TREATMENT...

This utilized an in-depth data analytics and feature engineering which involved identifying the numerical and categorical features and had them treated appropriately
for efficient machine learning.

Training dataset had to undergo some scaling in order to ensure numerical parity accross featured columns.

I did notice a sharp imbalance on the target feature, so had to do some over-sampling for beter model performance.

I ran the now treated dataset through a few models amongst which the Decision Tree Classifier model came out tops after arriving at the following hyperparameters:
*'criterion': 'entropy', 
*'max_depth': 11, 
*'max_features': None

through a memorandum of hyperparameter tuning using cross valiation scores and GridSearchCV.
