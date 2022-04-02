# Telecom_Churn: ML_Random Forest+Gradient-Boosting-
**Problem statement**

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.  For many incumbent operators, retaining high profitable customers is the number one business goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn, and identify the main indicators of churn.  In this competition, your goal is to build a machine learning model that is able to predict churning customers based on the features provided for their usage.  

**Customer behaviour during churn:**
Customers usually do not decide to switch to another competitor instantly, but rather over a period of time (this is especially applicable to high-value customers). In churn prediction, we assume that there are three phases of customer lifecycle :

1. The ‘good’ phase: In this phase, the customer is happy with the service and behaves as usual.

2. The ‘action’ phase: The customer experience starts to sore in this phase, for e.g. he/she gets a compelling offer from a competitor, faces unjust charges, becomes unhappy with service quality etc. In this phase, the customer usually shows different behaviour than the ‘good’ months. It is crucial to identify high-churn-risk customers in this phase, since some corrective actions can be taken at this point (such as matching the competitor’s offer/improving the service quality etc.)

3. The ‘churn’ phase: In this phase, the customer is said to have churned. In this case, since you are working over a four-month window, the first two months are the ‘good’ phase, the third month is the ‘action’ phase, while the fourth month (September) is the ‘churn’ phase.

**Steps Involved:**
1.Importing Libraries
2.Loading and Analysing the DATA
3. Data Cleaning & Manipulation
4. Handling Outliers and Null Values
5. Exploratory Data Analysis (EDA): Univariate and Bivariate Analysis 
6. Splitting the Data into Training and Testing Sets
7. Pricipal Component Analysis (PCA)
8. Model Building: 
 a)  Baseline Model-Logistic Regression
 b) Model Building using Random Forest
 c) Model Building using Cross VALIDATION
 d) Model Building using Hyperparameter tuning for RANDOM FOREST CLASSIFIER
 e) Model Building using Gradient Boosting
9. Making Predictions
10. Model Evaluation

**Libraries Used:**
1. NumPy as np
2. Pandas as pd
3. Matplotlib.pyplot as plt
4. Seaborn as sns
5. RandomForestClassifier
6. from sklearn.model_selection import GridSearchCV
7. GradientBoostingClassifier 
 
**Model Evaluation:** 
1. **Logistic Regression**:

    a) Accuracy Score :  92.72
    
    b) ROC AUC score :  59.07
    
    c) Precision score :  30.88
    
    d) Recall score :  21.03
    
 **2. Random Forest:**
 
    a) Accuracy Score :  94.23
    
    b) ROC AUC score :  50.1
     
   3. **Cross Validation:**
 
    a) Cross val score for Logistic regression= 0.6814756976043074
    
    b) Cross val score for Random Forest Classifier= 0.9466645964322385
    
  4. **Hyperparameter tuning for RANDOMFOREST CLASSIFIER**:
  
     Best estimator:
     RandomForestClassifier(max_depth=20, max_features=11, min_samples_leaf=20,
                       n_jobs=-1, 'n_estimators': 100, random_state=42)
     Best score:0.897284302897916
     
   **5. Gradient Boosting: The average validation accuracy across our 5 folds is 0.9401249213957866**
  

