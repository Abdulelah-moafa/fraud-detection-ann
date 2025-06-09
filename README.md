# Fraud Detection Using ANN

This project uses an Artificial Neural Network (ANN) to detect fraudulent credit card transactions.

## 📊 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transactions
- Highly imbalanced (fraud cases ≈ 0.17%)

## ⚙️ Model Architecture

- Input layer: 30 features
- Hidden layers:
  - Dense(32) with ReLU
  - Dense(16) with ReLU
- Output layer: Dense(1) with Sigmoid

## 🧪 Metrics

| Metric       | Value     |
|--------------|-----------|
| Accuracy     | ~99%      |
| Precision    | High      |
| Recall       | Good      |
| ROC AUC      | ~0.98     |

## 🛠 Tools

- Python 🐍
- TensorFlow / Keras 🤖
- scikit-learn 📊
- Google Colab ☁️

## ✅ How to Run

1. Upload `creditcard.csv`
2. Run the notebook `fraud_detection_ann.ipynb`
3. The model will train and evaluate
4. Download `fraud_detection_ann_model.h5`

## 📌 Note

Imbalanced classification is tricky — metrics like Precision, Recall, and AUC are more useful than Accuracy.

