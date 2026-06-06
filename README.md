# Bank Customer Churn Prediction

Predict whether a bank customer will leave the bank using machine learning models implemented from scratch.

## Models Implemented

- Neural Network from Scratch
- Linear SVM from Scratch

## Dataset

The dataset contains customer information from a bank and is used to predict customer churn (whether a customer leaves the bank).

Dataset files:
- train.csv
- test.csv

### Features
- CustomerId
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary

### Target Variable
- Exited
  - 0 = Customer stays
  - 1 = Customer leaves

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Results

- Neural Network Accuracy: 78.93%
- Linear SVM Accuracy: 21.07%

## How to Run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook customer_churn_prediction.ipynb
```

## Project Structure

```text
bank-customer-churn-prediction/
│
├── customer_churn_prediction.ipynb
├── train.csv
├── test.csv
└── README.md
```
