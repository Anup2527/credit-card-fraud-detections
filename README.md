# Credit Card Fraud Detection

This project detects fraudulent credit card transactions using machine learning.

## 🔍 Overview
- Dataset: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- ML Models: Logistic Regression, Random Forest
- Tools: Python, scikit-learn, pandas, matplotlib

## 📁 Project Structure
```
credit-card-fraud-detection/
├── data/              # Raw dataset (not included in repo)
├── notebooks/         # EDA and experimentation
├── src/               # Scripts for preprocessing, training, and prediction
├── saved_models/      # Trained models
├── requirements.txt   # Python dependencies
└── README.md          # Project documentation
```

## 🚀 How to Run
1. Place `creditcard.csv` in the `data/` folder.
2. Run preprocessing:
    ```bash
    python src/preprocess.py
    ```
3. Train the model:
    ```bash
    python src/train_model.py
    ```
4. Predict a transaction using `predict.py`.

## ✅ Status
Ready for use and experimentation.