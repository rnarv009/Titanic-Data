# Titanic Data

 # 1 - Goal
 
       * In this problem we have to predict if a passenger survived the sinking of the Titanic or not. 
       * For each PassengerId in the test set, you must predict a 0 or 1 value for the Survived variable.
 # 2 - Variable
               1.survival
               2.pclass
               3.sex
               4.Age
               5.sibsp
               6.parch
               7.ticket
               8.fare
               9.cabin
               10.embarked
 # 3 - Data Preprocessing 
                          Since this dataset is combination of numerical data and categorical data that is why I changed the categorical data into numerical data using "LabelEncoder()".
# 4 - XGBOOST
              Train the model using "xgboost" algorithm.
# 5 - Prediction
                Predict the output for x_test using above trained model and save them into 'csv' file.
