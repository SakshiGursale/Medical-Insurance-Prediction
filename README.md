# Medical-Insurance-Prediction

### Objective :
The objective of this project is to develop a machine learning model that can predict medical insurance costs based on various demographic and health-related factors

## Steps:

### 1. Data Gathering:
We have data in csv format

### 2. Data Cleaning:
We check whether missing values present or not , we check data types of features and count of columns and rows using df.info() function

### 3.Exploratory Data Analysis (EDA):
We plot a bar plot and pie chart of various features and we check the relationship between the features and counts and variations of features and we check correlation between dependent and independent  features using heatmap 

### 4. Feature Engineering:
we perform onehot encoding on features which has object data type

### 5. Model Building:
We split data into two parts train and test usig train_test_split and we train a model using machine learning algorithm here we use RandomForestRegressor() algorithm
and to reduce overfitting problem we perform hyperparameter tuning so that we get appropriate results and we predict the values.

### 6. Model Evaluation:
For evaluation we check R2_Score , Mean squared error (MSE) and Mean absolute error (MAE), We check accuracy of model using R2_Score Because R2_score is called as goodness of fit so we can check how good our model is fitted and we get 87% accuracy
