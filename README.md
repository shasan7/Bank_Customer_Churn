Predicting Bank Credit Card Customer Churn using the Credit Card Customers dataset (https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers).

Used scikit-learn's machine learning models for prediction. Logistic Regression, Random Forest, Support Vector Machine, XGBoost, CatBoost, Ridge Classifier and SGD Classifiers were run.


Obtained the following results:

Classifiers:  LogisticRegression has a score of 85.0 % accuracy score.

Classification Report: 

               precision    recall  f1-score   support

           0       0.97      0.85      0.90      1684
           1       0.52      0.84      0.64       324
    accuracy                           0.85      2008
    macro avg      0.74      0.84      0.77      2008
    weighted avg   0.89      0.85      0.86      2008
    
    Confusion Matrix: 
     [[1427  257]
     [  51  273]] 

 
Classifiers:  RandomForestClassifier has a score of 96.0 % accuracy score.

Classification Report: 

               precision    recall  f1-score   support

           0       0.96      0.99      0.97      1684
           1       0.92      0.80      0.85       324
    accuracy                           0.96      2008
    macro avg      0.94      0.89      0.91      2008
    weighted avg   0.96      0.96      0.95      2008
    
    Confusion Matrix: 
     [[1662   22]
     [  66  258]] 


Classifiers:  RidgeClassifier has a score of 84.0 % accuracy score.

Classification Report: 

               precision    recall  f1-score   support

           0       0.97      0.84      0.90      1684
           1       0.51      0.85      0.64       324
    accuracy                           0.84      2008
    macro avg      0.74      0.85      0.77      2008
    weighted avg   0.89      0.84      0.86      2008
    
    Confusion Matrix: 
     [[1418  266]
     [  47  277]] 


Classifiers:  SGDClassifier has a score of 83.0 % accuracy score.

Classification Report: 

               precision    recall  f1-score   support

           0       0.97      0.83      0.89      1684
           1       0.49      0.85      0.62       324
    accuracy                           0.83      2008
    macro avg      0.73      0.84      0.76      2008
    weighted avg   0.89      0.83      0.85      2008
    
    Confusion Matrix: 
     [[1396  288]
     [  50  274]] 


Classifiers:  SVC has a score of 93.0 % accuracy score.

Classification Report: 

               precision    recall  f1-score   support

           0       0.98      0.94      0.96      1684
           1       0.73      0.88      0.80       324
    accuracy                           0.93      2008
    macro avg      0.85      0.91      0.88      2008
    weighted avg   0.94      0.93      0.93      2008
    
    Confusion Matrix: 
     [[1578  106]
     [  38  286]] 


Classifiers:  XGBClassifier has a score of 97.0 % accuracy score.

Classification Report: 

               precision    recall  f1-score   support

           0       0.98      0.99      0.98      1684
           1       0.94      0.90      0.92       324
    accuracy                           0.97      2008
    macro avg      0.96      0.94      0.95      2008
    weighted avg   0.97      0.97      0.97      2008
    
    Confusion Matrix: 
     [[1666   18]
     [  33  291]] 


Classifiers:  CatBoostClassifier has a score of 97.0 % accuracy score.

Classification Report: 

               precision    recall  f1-score   support

           0       0.99      0.97      0.98      1684
           1       0.85      0.96      0.90       324
    accuracy                           0.97      2008
    macro avg      0.92      0.96      0.94      2008
    weighted avg   0.97      0.97      0.97      2008
    
    Confusion Matrix: 
     [[1631   53]
     [  14  310]] 
