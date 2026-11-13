# Customer Purchase Prediction using Logistic Regression

## Project Overview

This project uses **Logistic Regression** to predict whether a customer will purchase a product based on customer behavior and demographic information.

## Objective

The goal is to build a machine learning classification model that predicts:

- `0` → No Purchase
- `1` → Purchase

## Features Used

The model uses the following features:

- **Age**
- **Annual Income**
- **Website Time**
- **Previous Purchases**

### Target Variable

- **Purchased**

## Machine Learning Workflow

1. Created the customer dataset
2. Explored and understood the dataset
3. Performed Exploratory Data Analysis (EDA)
4. Selected features and target
5. Split the data into training and testing sets
6. Trained a Logistic Regression model
7. Generated predictions
8. Generated prediction probabilities
9. Evaluated the model
10. Predicted purchase behavior for a new customer

## Model Evaluation

The model was evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score

## New Customer Prediction

The trained model was also used to predict whether a new customer would purchase a product based on their:

- Age
- Annual Income
- Website Time
- Previous Purchases

## Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## Project Files

- `customer_purchase_prediction.ipynb` — Complete Google Colab notebook containing the dataset, analysis, model training, predictions, and evaluation.

## Conclusion

This project demonstrates how **Logistic Regression** can be used for a real-world binary classification problem. The model predicts customer purchase behavior and provides both the predicted class and probability of purchase.
