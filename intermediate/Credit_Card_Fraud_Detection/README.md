# 💳 Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning. Due to the high imbalance between normal and fraud cases, the project demonstrates how to deal with such datasets effectively and evaluate model performance beyond just accuracy.

---

## 📊 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Description: Contains 284,807 transactions made in September 2013 by European cardholders.
- Target column: `Class`  
  - `0` → Legitimate transaction  
  - `1` → Fraudulent transaction

---

## 🧠 ML Concepts Used

- Logistic Regression
- Train-Test Split
- Data Preprocessing & Feature Scaling
- Handling Imbalanced Data (Under-sampling)
- Model Evaluation: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

---

## 🔍 Project Workflow

1. **Data Exploration**  
   - No missing values
   - Highly imbalanced target class (fraud ≈ 0.17%)

2. **Preprocessing**  
   - Dropped `Time` column  
   - Scaled `Amount` using `StandardScaler`

3. **Baseline Model (Imbalanced Data)**  
   - Trained Logistic Regression  
   - High accuracy, low recall for fraud

4. **Balancing the Dataset (Under-sampling)**  
   - Equal number of fraud and normal transactions  
   - Retrained model for better fraud detection

5. **Evaluation**  
   - Improved recall and F1-score for fraudulent class

---

## 📚 Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
