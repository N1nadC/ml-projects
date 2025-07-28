# 💓 Heart Disease Prediction using Machine Learning

## 📌 Project Objective
The goal of this project is to build a machine learning model that can accurately predict whether a person is likely to have heart disease based on various medical and personal attributes. Early detection of heart disease is crucial for timely intervention and treatment.

---

## 🧠 Problem Statement
Heart disease is one of the leading causes of death worldwide. Predicting the presence of heart disease in a patient can significantly aid healthcare providers in diagnosis and treatment planning. This project leverages supervised learning to classify whether a person has heart disease (1) or not (0).

---

## 📊 Dataset Description
The dataset used contains various medical attributes of patients. Below are the key features:

| Feature      | Description |
|--------------|-------------|
| `age`        | Age of the patient |
| `sex`        | Gender (1 = male, 0 = female) |
| `cp`         | Chest pain type (0–3) |
| `trestbps`   | Resting blood pressure (mm Hg) |
| `chol`       | Serum cholesterol in mg/dl |
| `fbs`        | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| `restecg`    | Resting electrocardiographic results |
| `thalach`    | Maximum heart rate achieved |
| `exang`      | Exercise-induced angina (1 = yes; 0 = no) |
| `oldpeak`    | ST depression induced by exercise |
| `slope`      | Slope of the peak exercise ST segment |
| `ca`         | Number of major vessels colored by fluoroscopy (0–3) |
| `thal`       | Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible defect) |
| `target`     | Target variable (0 = no heart disease, 1 = heart disease) |

---

## ⚙️ Technologies Used
- Python
- Pandas & NumPy (Data handling)
- Seaborn & Matplotlib (EDA & Visualization)
- Scikit-learn (Model building and evaluation)

---

## 🚀 Workflow
1. **Data Collection** – Dataset from open-source repositories (Kaggle / UCI).
2. **Data Preprocessing** – Handling missing values, categorical encoding, feature scaling.
3. **Exploratory Data Analysis (EDA)** – Understanding data distribution and feature relationships.
4. **Model Building** – Logistic Regression used as the base classifier.
5. **Model Evaluation** – Accuracy, Confusion Matrix, Classification Report, ROC-AUC curve.

---

## 📈 Results
The logistic regression model achieved good performance with:
- **Accuracy**: ~86%
- **ROC AUC Score**: ~0.90
- Balanced precision and recall across both classes.

---

## ✅ Conclusion
This project demonstrates how machine learning techniques can be used for effective medical predictions. The model provides reliable predictions and could assist medical professionals in detecting heart disease at an early stage.

---

