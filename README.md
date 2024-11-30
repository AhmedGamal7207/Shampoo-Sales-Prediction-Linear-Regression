# Shampoo Sales Prediction Using Linear Regression

## Overview
This project uses a Linear Regression model to predict shampoo sales based on historical data. The model is trained on a dataset containing monthly sales data, and the predictions are evaluated using Mean Squared Error (MSE). The project includes training, testing, and predicting future sales.

## Dataset

The dataset `shampoo_sales.csv` contains monthly sales data over 36 months. The data is used to train the Linear Regression model and predict future sales.

## Libraries Used

- `numpy`: For numerical operations.
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualization and plotting.
- `sklearn`: For machine learning algorithms and evaluation.

## Workflow

### 1. Data Preprocessing
The dataset is read and preprocessed:
- The month column is encoded using `LabelEncoder`.
- The dataset is split into training and testing sets using `train_test_split`.

### 2. Model Training
A Linear Regression model is trained on the training set using `regressor.fit()`. 

### 3. Model Evaluation
The model is evaluated using Mean Squared Error (MSE) to assess its prediction accuracy.

### 4. Visualization
The training and testing data are visualized using scatter plots and regression lines. This allows for a clear understanding of the model's predictions and how it fits the actual sales data.

### 5. Future Sales Prediction
The trained model is used to predict shampoo sales for future months (e.g., month 40).
