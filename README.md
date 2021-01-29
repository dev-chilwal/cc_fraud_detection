# cc_fraud_detection

A credit card company wants to detect potential fraud cases so that the customers are ensured that they won’t be charged for the items they did not purchase. The dataset containing the transactions between people and the information that they are fraud or not. The objective is to tackle this situation by building classification models to classify and distinguish fraud transactions.

Data used for the problem:
https://www.kaggle.com/mlg-ulb/creditcardfraud?select=creditcard.csv

Models tested:
1. Logistic Regression
2. Random Forest
3 XGBoost
4. Stacked model(Logistic Regression, RandomForest, XGBoost with Logistic Regression as final estimator)

Metric used:
As the dataset is significantly imbalanced, accuracy wouldn;t be a good score. ROC-AUC and/or F1 score will be a better metric to chose and compare models.

Model results:
1. Logistic Regression

![Alt text](results/log_reg_model.png?raw=true "Score Logistic Regression")

2. Random Forest

![Alt text](results/rf_model.png?raw=true "Score RandomForest Classifier")

3 XGBoost

![Alt text](results/xgboost_model.png?raw=true "Score XGBoost Classifier")

4. Stacked model(Logistic Regression, RandomForest, XGBoost with Logistic Regression as final estimator)

![Alt text](results/stacked_model.png?raw=true "Score Stacked Classifier")

Scores: 

![Alt text](results/score.png?raw=true "Scores")

