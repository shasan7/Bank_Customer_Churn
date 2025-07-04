# Predicting Bank Credit Card Customer Churn using the Credit Card Customers dataset

## Dataset Link: https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers

## Kaggle Notebook: https://www.kaggle.com/code/shasan7/bank-churn

Used scikit-learn's machine learning models for prediction. Logistic Regression, Random Forest, Support Vector Machine, XGBoost, CatBoost, Ridge Classifier and SGD Classifiers were run.

**The XGBoost attained an accuracy of 97% with an F1-Score of 0.94**, performing best among the machine learning algorithms. 
We trained it with 100 estimators using the "logloss" evaluation metric, and 'balanced' value was passed to the class_weights parameter to provide attention to the minority class, **which is crucial for a dataset like ours with huge class imbalance**.

Obtained the following results:

Classifiers:  LogisticRegression has a score of 85.0 % accuracy score.

    Classification Report: 
  
               precision    recall  f1-score   support

           0       0.96      0.86      0.91      1701
           1       0.52      0.81      0.63       325

    accuracy                           0.85      2026
    macro avg      0.74      0.83      0.77      2026
    weighted avg   0.89      0.85      0.86      2026

    Confusion Matrix: 
     [[1461  240]
     [  63  262]] 


Classifiers:  RandomForestClassifier has a score of 95.0 % accuracy score.

    Classification Report: 
  
               precision    recall  f1-score   support

           0       0.96      0.99      0.97      1701
           1       0.93      0.77      0.84       325

    accuracy                           0.95      2026
    macro avg      0.94      0.88      0.91      2026
    weighted avg   0.95      0.95      0.95      2026

    Confusion Matrix: 
     [[1683   18]
     [  76  249]] 


Classifiers:  RidgeClassifier has a score of 84.0 % accuracy score.

    Classification Report: 
  
               precision    recall  f1-score   support

           0       0.96      0.85      0.90      1701
           1       0.51      0.81      0.63       325

    accuracy                           0.84      2026
    macro avg      0.73      0.83      0.76      2026
    weighted avg   0.89      0.84      0.86      2026

    Confusion Matrix: 
     [[1448  253]
     [  62  263]] 


Classifiers:  SGDClassifier has a score of 84.0 % accuracy score.

    Classification Report: 
  
               precision    recall  f1-score   support

           0       0.96      0.85      0.90      1701
           1       0.50      0.80      0.62       325

    accuracy                           0.84      2026
    macro avg      0.73      0.83      0.76      2026
    weighted avg   0.88      0.84      0.86      2026

    Confusion Matrix: 
     [[1446  255]
     [  65  260]] 


Classifiers:  SVC has a score of 93.0 % accuracy score.

    Classification Report: 
  
               precision    recall  f1-score   support

           0       0.97      0.94      0.95      1701
           1       0.73      0.84      0.78       325

    accuracy                           0.93      2026
    macro avg      0.85      0.89      0.87      2026
    weighted avg   0.93      0.93      0.93      2026

    Confusion Matrix: 
     [[1601  100]
     [  51  274]] 


Classifiers:  CatBoostClassifier has a score of 96.0 % accuracy score.

    Classification Report: 
  
               precision    recall  f1-score   support

           0       0.99      0.97      0.98      1701
           1       0.85      0.93      0.89       325

    accuracy                           0.96      2026
    macro avg      0.92      0.95      0.93      2026
    weighted avg   0.96      0.96      0.96      2026

    Confusion Matrix: 
     [[1647   54]
     [  23  302]] 


Classifiers:  XGBClassifier has a score of 97.0 % accuracy score.

    Classification Report: 
  
               precision    recall  f1-score   support

           0       0.97      0.99      0.98      1701
           1       0.93      0.86      0.90       325

    accuracy                           0.97      2026
    macro avg      0.95      0.92      0.94      2026
    weighted avg   0.97      0.97      0.97      2026

    Confusion Matrix: 
     [[1681   20]
     [  45  280]] 


Feature importance for the XGBoost Classifier:

![Feature Importance: ](Feature_Importance_XGBoost.png)
