# credit_card_fraud_detection
## Overview
This project is a machine learning pipeline for detecting fraudulent credit card transactions. Using various machine learning techniques and models, it aims to classify transactions as either legitimate or fraudulent based on features like transaction type, amount, and other factors.
## Prerequisites
To run this project, you need to have the following python libraries installed:
- numpy
- pandas
- scikit-learn
To install the necessary packages, run the following command:

```bash
pip install joblib numpy scikit-learn pandas nltk
```
##Files
- `model1`:A pickled Logistic Regression model for detecting potential credit card frauds.
- `creditcard`:The dataset contains transactions made by credit cards in September 2013 by European cardholders.
## How to use
1. Load models and data
2. run the scripts
3. testing by test cases
## Example usage
```bash
test_input = np.array([[2014, 'ACURA', 'ILX', 'COMPACT', 2.0, 4, 'AS5', 'Z', 9.9, 6.7, 8.5, 33]])

predicted_output = model.predict(test_input)
```
