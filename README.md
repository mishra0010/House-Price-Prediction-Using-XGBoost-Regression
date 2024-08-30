@ Author - Harshit Mishra

---

# House Price Prediction Model Using XGBoost

## Project Overview
This project involves building a house price prediction model using the XGBoost regression algorithm. The model has been trained and tested on the Boston Housing dataset from the sklearn library. With an impressive accuracy of 90% on the test data, this model is a reliable tool for predicting house prices based on various features.

## Dataset
- **Source**: Boston Housing Dataset (from sklearn library)
- **Description**: The dataset contains 506 samples and 13 feature variables related to housing in Boston, including average number of rooms per dwelling, property tax rate, and pupil-teacher ratio by town.

## Model
- **Algorithm**: XGBoost Regression
- **Accuracy**: 90% on test data
- **Features Used**:
  - CRIM: Per capita crime rate by town
  - ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.
  - INDUS: Proportion of non-retail business acres per town
  - CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
  - NOX: Nitric oxide concentration (parts per 10 million)
  - RM: Average number of rooms per dwelling
  - AGE: Proportion of owner-occupied units built prior to 1940
  - DIS: Weighted distances to five Boston employment centers
  - RAD: Index of accessibility to radial highways
  - TAX: Full-value property tax rate per $10,000
  - PTRATIO: Pupil-teacher ratio by town
  - B: 1000(Bk - 0.63)^2 where Bk is the proportion of black residents by town
  - LSTAT: Percentage of lower status of the population


## Usage
- **Input**: The model accepts input features related to housing characteristics.
- **Output**: Predicts the house price based on the input features.

## Features
- **High Accuracy**: The model achieved 90% accuracy on the test set, making it a reliable predictor for house prices.
- **Efficient**: The use of XGBoost ensures fast and efficient computation, suitable for large datasets.

## Future Work
- Improve the model’s accuracy by tuning hyperparameters.
- Explore the use of additional features or alternative datasets.
- Implement a web-based interface for easy user interaction.



![workflow](https://github.com/user-attachments/assets/c6f1c78e-07d4-4a94-a376-8cfe0e966043)
