# House_Valuation_Prediction
### Project Overview
This project aims to build a model that values housing property  using the features in a house, environmental factor, and ocean proximity, thereby enhancing real estate decisions.  Relationship between all data input points are compared with the target variable  and inferences are drawn based om there correlation values.
### Tools
- MS Excel -Data Cleaning
- Python Programming Language- EDA and visualization
### Libraries
- Jupyter notebook
- Pandas
- Numpy
- SckitLearn
- Seaborne and Matplotlib
### Data Cleaning and Sorting
It involves cleaning data to remove null/missing values or using an imputer class to compute the mean, median or mode where data are missing/null.
### Data Processing
1. One hot encoder: This divides all categorical variable to individual column representing them with dummy variables
2. Feature Engineering:  It involve separating the input variable from the target variable.
3. Data Visualization: It involve displaying the target class in a scatterplot to determine the best model to use based on the data points distribution.
4. Adjusting imbalanced dataset- This is achieved using undersampling or oversampling method with the smote class
### Data Splitting
If the data set are not splitted originally, a test_train_split class from sklearn is used to achieve this. But if the data is seperated into train and test data on differnt spreadsheet. Then it is necessary you tag them as X_train, X_test, Y_train, Y_test.
### Data Rescaling
The StandardScaler is used to fit and Transform the X_train, then transform the X_test to have mean value of 0 and standard deviation of 1.
### Model Training
Based on the distribution of data points, a linear regression is used to train the model
###  Evaluation
The model was fitted and the accuracy, precision, recall and f1 score were determined using the classification_report class.
The accuracy was found to be 95%.
### Recommendation
Hyperparameter tuning can be employed to iterate through all other supervised machine learning algorithm to geth the best performer. This involve using GridSearchCV class