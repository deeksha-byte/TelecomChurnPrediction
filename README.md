# TelecomChurnPrediction

## Table of Contents
### 1. Set-up
#### 1.1 Import Libraries
#### 1.2 Import Data
#### 1.3 Data Set Characteristics
#### 1.4 Dataset Attributes
### 2. Exploring data set
#### 2.1 Quick overview
### 3. Data preprocessing
#### 3.1 Dealing with missing values
#### 3.2 Dealin with error: could not convert string to float:
#### 3.3 Dealing with duplicated values
#### 3.4 Creating numerical and categorical lists
#### 3.5 Label Encoding
#### 3.6 Train dataset - Basic statistics
### 4. Data imbalance check
#### 4.1 Imbalanced data requires different approach
#### 4.2 Choosing the most suitable metrics
### 5. EDA
#### 5.1 Checking distributions
#### 5.2 Checking for outliers - Inter Quartile Range (IQR)
#### 5.3 Numerical Features vs Target Variable (Churn)
#### 5.4 Summary
#### 5.5 Categorical Features vs Target Variable (Churn)
##### 5.5.1 Customer information: Gender, SeniorCitizen, Partner, Dependents
##### 5.5.2 Provided services: PhoneService, MultipleLines, InternetService, StreamingTV, StreamingMovies
##### 5.5.3 Support services: OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport
##### 5.5.4 Payments: Contract, PaperlessBilling, PaymentMethod
### 6. Feature Engineering
#### 6.1 Train test split - stratified splitting
#### 6.2 Feature scaling
#### 6.3 One hot Encoder
##### 6.3.1 What have we done?
##### 6.3.2 Test data set
### 7. Model building
#### 7.1 Feature importance
#### 7.2 Baseline - Random Forest
##### 7.2.1 K-Fold Cross-validation
##### 7.2.2 Hyperparameter Tuning Using GridSearchCV
##### 7.3.1 K-Fold Cross-validation
#### 7.3 Adding another classifier - XGBoost
##### 7.3.1 K-Fold Cross-validation
##### 7.3.2 Hyperparameter Tuning Using GridSearchCV
##### 7.3.3 K-Fold Cross-validation
#### 7.4 Voting Clasifier
##### 7.4.1 K-Fold Cross-validation
### 8. Result comparison
#### 8.1 AUC-ROC Curve for the best algorithm
#### 8.2 Precision-Recall Curve (PR curve) for the best algorithm
