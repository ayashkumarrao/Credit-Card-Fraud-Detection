![Python](https://img.shields.io/badge/Python-3.x-red) ![ML](https://img.shields.io/badge/Machine-Learning-blue) ![Status](https://img.shields.io/badge/Status-Completed-success) ![DS](https://img.shields.io/badge/Data-Science-ff69b4)

# Credit-Card-Fraud-Detection

_Dataset link_:
[[ Link ]](https://www.kaggle.com/mlg-ulb/creditcardfraud)

_Dataset size_:
2,79,191 x 31 [ rows x columns ] 

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

<u>Problem formulation</u> :

1. Explore and Process the data in order to glean basic insights about the data and prep to utilize models

2. Finding a classification model that works best with the data.

3. Given the data and model performance, determine what is the best course of actions going forward.

## Approach:

* EDA 

* Preprocessing

* Model data
  Classification 
        * Logistic Regression got F1 score on training data of 0.9435
        * Logistic Regression got F1 score on test data of 0.9282
        * Decision Tree got F1 score on training data of 1.0
        * Decision Tree got F1 score on test data of 0.9076
        * Support Vector Machine got F1 score on training data of 0.5288
        * Support Vector Machine got F1 score on test data of 0.5384
        * K-Nearest Neighbors got F1 score on training data of 0.7522
        * K-Nearest Neighbors got F1 score on test data of 0.5794

* Summarize Findings and Proposed Further Work

# Conclusions
In this case, we cleaned up and featurized dataset and built some classification models on these featurizations to predict Class. Using the methond of under sampling we were able to get our logistic regression model accuracy up to 93%.
