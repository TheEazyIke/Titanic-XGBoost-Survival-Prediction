# Titanic-XGBoost-Survival-Prediction

### Overview
Utilized XGBoost machine learning model in Python to classify passengers on board the Titanic, in order to predict if they survived or not.

### Preprocessing/Feature Engineering
Transformed the features to correct incomplete data, make them more efficient for model performance, and create new features.

Methods Implemented:
- Data Imputation using KNN
- One Hot Encoding
- Binary Dummy Variable
- Floor_Level feature was created by taking the first element of Cabin entries and then performing One Hot Encoding

### Model Creation
Trained XGBoost model to final classification accuracy score of 84.75%

Steps:
- Split training data in 75%:25% portion to create validation set
- Trained 3 models with different hyperparameters to test which was most effective
- Final model hyperparameters were:
  - Learning_Rate = 0.03
  - Max_Depth = 7
  - N_Estimators = 1000
  - Early_Stopping_Rounds = 5
 
  

  
