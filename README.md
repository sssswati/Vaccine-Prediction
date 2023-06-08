Vaccine Prediction:
This repository contains code for a vaccine prediction project focused on determining whether a patient has taken the vaccine or not. The project utilizes machine learning techniques, including Random Forest, Logistic Regression, and XGBoost, to train models capable of accurately predicting the vaccination status based on various features.

Dataset:
The dataset used for this project consists of a collection of patient records with corresponding vaccination status labels. The dataset contains several features such as age, gender, medical history, and more, which are used to predict the vaccination status. The dataset can be obtained from the attached csv file.

Exploratory Data Analysis (EDA):
Before building the prediction models, exploratory data analysis (EDA) is performed to gain insights into the dataset and understand the relationships between variables. 
The EDA process involves:
- Statistical summaries of the dataset.
- Data visualization using plots, histograms, heatmaps, and more.
- Handling missing values and outliers, if applicable.
- Feature engineering, including data transformation, scaling, and encoding.
Model Selection:
For this vaccine prediction project, three different models are implemented:

- Random Forest: Random Forest is an ensemble learning method that combines multiple decision trees to make predictions.
It is capable of handling complex relationships between features and producing accurate results.

- Logistic Regression: Logistic Regression is a widely used statistical model for binary classification problems. It models the relationship between the dependent variable and independent variables by estimating probabilities using a logistic function.

- XGBoost: XGBoost is a gradient boosting framework known for its speed and performance. It uses a combination of weak prediction models (decision trees) and gradient boosting techniques to improve accuracy and handle large datasets.


Results
The models achieved the following performance metrics on the test set:

~Random Forest:
-- Accuracy: 71%

~Logistic Regression:
-- Accuracy: 73%

~XGBoost:
-- Accuracy: 81%
