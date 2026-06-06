# Bank Customer Churn Prediction

Predict whether a bank customer will leave the bank using machine learning models implemented from scratch.

## Objective

Build machine learning models from scratch to predict customer churn and compare the performance of a Neural Network and a Linear SVM.

## Models Implemented

- Neural Network from Scratch
- Linear SVM from Scratch

## Dataset

The dataset contains customer information from a bank and is used to predict customer churn (whether a customer leaves the bank).

### Dataset Files

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

## Data Preprocessing

The following preprocessing steps were performed:

- Handling categorical variables using Label Encoding
- Feature scaling using StandardScaler
- Train-test split for model evaluation
- Feature selection and preparation for machine learning models

## Results

The results below were obtained using reduced training settings for faster experimentation and demonstration purposes.

### Neural Network

- Test Accuracy: **78.93%**
- Training Epochs Used: **3**

### Linear SVM

- Test Accuracy: **21.07%**
- Training Iterations Used: **20**

### Training Notes

The original implementation was designed to run with larger training settings:

| Model | Experimental Setting | Original Setting |
|---------|---------|---------|
| Neural Network | 3 Epochs | 10 Epochs |
| Linear SVM | 20 Iterations | 5000 Iterations |

Increasing the number of epochs and iterations generally improves model convergence and predictive performance but requires significantly longer training time.

The notebook contains the complete implementation and can be re-run with higher training settings for improved results.

## Visualizations

The notebook includes:

- Training Loss vs Validation Loss
- Training Accuracy vs Validation Accuracy
- Model Performance Evaluation Graphs

All generated plots and results are available directly within the Jupyter Notebook.

## Project Structure

```text
bank-customer-churn-prediction/
│
├── customer_churn_prediction.ipynb
├── train.csv
├── test.csv
└── README.md
```

## How to Run

### Clone Repository

```bash
git clone https://github.com/Shaista1509/bank-customer-churn-prediction.git
cd bank-customer-churn-prediction
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Launch Notebook

```bash
jupyter notebook customer_churn_prediction.ipynb
```

## Future Improvements

- Hyperparameter tuning
- Additional feature engineering
- Improved Neural Network architecture
- Enhanced SVM optimization
- Cross-validation for more robust evaluation

## Author

**Shaista**

Machine Learning Project: Bank Customer Churn Prediction using Neural Networks and Linear SVM implemented from scratch.
