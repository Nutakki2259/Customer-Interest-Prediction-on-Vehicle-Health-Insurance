# Three-Machine-Learning-Models-for-the-Prediction-of-Customer-Interest-on-Vehicle-Health-Insurance
Customer Interest on vehicle health insurance is evaluated from the best of 3 models i.e., Logistic Regression, KNN, Random Forest. 

## Pre-Requests:

## 1. Data Description
The data is taken from the Kaggle website 'Health Insurance Cross Sell Prediction' dataset. The data consits of 12 variable parameters of which 'Response' column is the target data. This column appears in train dataset where as test data consists of remaining 11 columns.

Response defines customer interest: 1 : Customer is interested, 0 : Customer is not interested

## 2. Loading Dataset
Before loading the dataset change the dataset path where the repositoory is downloaded. 
The dataset format are made into clear through **Data Mining**, cleaning and viewing for further process. Converting the Words representing in the data into my own designed format Numericals to better understand by model which is **Data Processing**.

## 3. Designing of Three Machine Learning Models (Logistic Regression, KNN, Random Forest)
The three models are designed on same dataset and evaluated to know the best model that defines the dataset. After clear observation, Random Forest Classifier has showed a score of 99.99% that is far bettr in using and later KNN is near to 90%. In this case the dataset is evaluated using Random Forest.

## 4. Evaluation by the Best Model (Random Forest)
The data is evaluated using Random Forest Classifier to show the performance in prediction of cutomer interest on vehicle health insurance. The model is saved for later use when requirement. This shows a better performance results. The performance of the model depends on the tuning of hyperparameters.

## 5. Vizualizing, Saving Results, Choosing Random 100 Data Points
The values obtained are vizualized and added a ''Response column to test data. The total test data is saved for better understanding. The 100 data points are chosen randomly from the test data and to show how the model predicted for the dataset. This showed the same results by the model in the previous section of the same test data.

## 6. References
Dataset: https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction?select=sample_submission.csv

