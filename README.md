# Machine-Learning-Models-for-Detecting-Credit-Card-Fraud

This project uses machine learning models to detect fraudulent credit card transactions. The primary goal is to build a model that can accurately classify transactions as fraudulent or legitimate.

## Dataset
- The dataset is sourced from [Kaggle's Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
- The dataset contains X rows and Y features including transaction amount, time, etc.

## Models Used
- Random Forest
- XGBoost

## Key Steps
1. Data cleaning and preparation.
2. Exploratory Data Analysis (EDA) to identify fraud patterns.
3. Feature engineering to improve model performance.
4. Model training and evaluation using AUC-ROC, Precision, and Recall.
5. Hyperparameter tuning to optimize model accuracy.

## Results
- Achieved an AUC-ROC of 0.95, reducing false positives by X%.

## How to Use
1. Clone the repository.
2. Install required packages using `pip install -r requirements.txt`.
3. Run `fraud_detection.py` to train the models.
