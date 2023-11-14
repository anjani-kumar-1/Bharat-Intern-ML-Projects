# Bharat-Intern-ML-Projects

# Task 1 -  House Price Predictor with Linear Regression

## Overview
This project involves building a linear regression model to predict house prices based on various features such as average area income, house age, number of rooms, number of bedrooms, and the population of the area. The dataset used for this analysis contains 5000 entries.

## Dataset
The dataset (`USA_Housing.csv`) includes the following columns:
- `Avg. Area Income`: Average income of residents in the city where the house is located.
- `Avg. Area House Age`: Average age of houses in the same city.
- `Avg. Area Number of Rooms`: Average number of rooms for houses in the same city.
- `Avg. Area Number of Bedrooms`: Average number of bedrooms for houses in the same city.
- `Area Population`: Population of the city where the house is located.
- `Price`: Price at which the house was sold.
- `Address`: Address of the house.

## Linear Regression Model
### Data Preprocessing
- Split the data into features (X) and the target variable (y).
- Conducted a train-test split (80% training, 20% testing).

### Model Training
- Utilized Linear Regression to train the model on the training set.

### Model Evaluation
- Printed the intercept and coefficients of the linear regression model.
- Interpreted coefficients to understand the impact of each feature on house prices.

### Predictions and Residuals
- Generated predictions on the test set.
- Plotted a scatter plot to visualize the relationship between actual and predicted house prices.
- Created a residual histogram to analyze the distribution of residuals.


#  Task 3 - Iris Flower Classification

## Overview
This project involves the classification of iris flowers into different species based on their sepal and petal characteristics. The dataset used for this analysis contains 150 samples of iris flowers, each belonging to one of three species: setosa, versicolor, or virginica.

## Dataset
The dataset (`iris.csv`) includes the following columns:
- `Unnamed: 0`: Index
- `Sepal.Length`: Length of the sepal
- `Sepal.Width`: Width of the sepal
- `Petal.Length`: Length of the petal
- `Petal.Width`: Width of the petal
- `Species`: Iris flower species (setosa, versicolor, or virginica)

## Data Preprocessing
- Separated the dataset into training and testing sets (75% training, 25% testing).
- Extracted features (`Sepal.Length`, `Sepal.Width`, `Petal.Length`, `Petal.Width`) and target variable (`Species`).

## Machine Learning Models
1. **Logistic Regression**
2. **Support Vector Machines (SVM)**
3. **K-Nearest Neighbors (KNN)**
4. **Gaussian Naive Bayes**
5. **Decision Tree**

## Conclusion
- The Guassian Naive Bayes model performed well in classifying iris flowers based on sepal and petal characteristics.
- The results can be further improved with hyperparameter tuning and additional feature engineering.


