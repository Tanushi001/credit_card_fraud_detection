# LegitX: credit_card_fraud_detection
## 📌 Project Overview
This project builds a machine learning model to detect fraudulent credit card transactions. The dataset is highly imbalanced (fraud cases are <1% of total), requiring specialized techniques to avoid false negatives. 

I implemented an **XGBoost Classifier**, which is widely regarded as the state-of-the-art algorithm for tabular data, to distinguish between legitimate and fraudulent activities.

## 🚀 Key Features
- **Algorithm:** XGBoost (Extreme Gradient Boosting) for high performance.
- **Imbalance Handling:** Tuned probability thresholds to prioritize Recall (catching as many frauds as possible).
- **Metrics:** Focused on **AUPRC** (Area Under Precision-Recall Curve) and **F1-Score** rather than simple accuracy.
- **Visualization:** Correlation heatmaps and Precision-Recall curves.

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy)
- **ML Engine:** XGBoost, Scikit-Learn
- **Visualization:** Seaborn, Matplotlib

## 📊 Performance
*Standard accuracy is misleading in fraud detection. A model that predicts "Safe" every time would be 99.8% accurate but useless.*

- **Precision (Fraud):** ~0.94 (Very few false alarms)
- **Recall (Fraud):** ~0.82 (Catches majority of fraud cases)
- **AUPRC:** 0.88

## 📂 Dataset
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
*Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)*

## ⚙️ How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
