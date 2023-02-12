# Predicting-Water-Well-Conditions-in-Tanzania
## 1.  Business Understanding
### Problem Statement
Lack of clean and potable water is a major issue in many communities across Tanzania. To address this issue, the Tanzania Ministry of Water has installed several water wells across the country.
However, not all of these wells are functioning as intended, which results in lack of access to clean water for communities.
The goal of this project is to use data from Taarifa and the Tanzania Ministry of Water to predict which pumps are functional, which need some repairs, and which don't work at all.
This will be achieved by building a classifier model that can accurately predict the condition of water wells in Tanzania based on the variables provided in the data. By doing so, the aim is to improve maintenance operations and ensure that clean and potable water is available to communities across Tanzania.

### Research Question
Which classifier model can accurately predict the condition of water wells in Tanzania?

### Objectives
#### Main Objective
To predict the condition of water wells in Tanzania to ensure that clean and potable water is available to communities across Tanzania.
#### Specific Objectives
To understand the problem statement and the goal of the project
 To identify the variables that can impact the functionality of water wells
 To determine the target variable (functional, need repairs, or non-functional)
 
### Metric of Success
The model will be considered a success when both accuracy and f1 score are between 0.8 to 1.

## 2. Data Understanding
![download](https://user-images.githubusercontent.com/71209567/218337773-7a0d06dc-ef2f-4e17-adf3-472e4d730454.png)

The majority class is the functional class while the minority is the functional needs repair class
 
## 3. Data Preparation
Data Cleaning
Feature Selection
Encoding Categorical Variables
Scaling
Handling Class Imbalance

## 4. Modeling
The Random Forest Classifier model has an accuracy of 0.8150 and an F1 score of 0.8081
In terms of accuracy, the random forest classifier has a higher accuracy score of 0.81 compared to the other 4 models, which had accuracy scores of 0.75 (gradient boosting), 0.76 (KNN), 0.72 (decision tree), and 0.70 (logistic regression).
In terms of the F1 score, the random forest classifier has a higher F1 score of 0.81 compared to the other 4 models, which had F1 scores of 0.74 (gradient boosting), 0.75 (KNN), 0.70 (decision tree), and 0.68 (logistic regression).
Based on these results, the random forest classifier appears to be performing the best among the 5 models. 
Hyperparameter tuning and cross-validation is performed because they help to optimize the model performance and prevent overfitting or underfitting.
The randomized search cross-validation helps to perform an efficient search for the optimal hyperparameters and cross-validate the model, which leads to better model performance and robustness.
The accuracy of the model is 0.82424, which means that the model correctly predicted the class label of 82.4% of the test data instances.
The F1 score is 0.8157. A higher F1 score indicates a better performance of the model.
This tuned model has better performance metrics and hence a good model.

 
## 6. Conclusion and Recommendations
### Conclusion
The model could be further improved by incorporating more data especially for the functional needs repair class to handle imbalance for the classes

### Recommendations
1. The Tanzania Ministry of Water should invest in better waterpoint types such communal standpipes and hand pumps
2. The Tanzania Ministry of Water should ensure that the extraction type for the wells is mostly through gravity and handpump
3. The Tanzania Ministry of Water should ensure that the gps height(altitude of the well) for most water points is high enough
4. The Tanzania Ministry of Water should also ensure that the people using the waterpoints pay either monthly, annually or per bucket to ensure that the wells are well maintained
 
 

