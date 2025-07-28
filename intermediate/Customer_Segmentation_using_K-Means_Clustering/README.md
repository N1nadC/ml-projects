# 🛍️ Customer Segmentation using K-Means Clustering

This project demonstrates how to segment mall customers into meaningful groups using **unsupervised machine learning** (K-Means Clustering). The goal is to help businesses understand customer types based on their demographics and spending behavior.

---

## 📊 Dataset

- Source: [Mall Customers Dataset](https://github.com/mwaskom/seaborn-data/blob/master/mall_customers.csv)
- Features:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

---

## 🧠 ML Concepts Used

- K-Means Clustering
- Elbow Method (using Inertia)
- Silhouette Score
- Data Preprocessing & Scaling
- Cluster Visualization

---

## 📌 Project Workflow

1. **Data Loading & Exploration**
   - Checked for missing values
   - Explored distribution of gender, age, income, and spending

2. **Data Preprocessing**
   - Encoded gender
   - Selected relevant features
   - Scaled data using `StandardScaler`

3. **Choosing Optimal Clusters**
   - Used **Elbow Method** (k=5)
   - Validated with **Silhouette Score**

4. **Applying K-Means**
   - Clustered customers into 5 segments
   - Added cluster labels to the dataset

5. **Visualization**
   - Plotted Annual Income vs Spending Score with cluster coloring

---

## 📈 Conclusion

- Customers were grouped into **5 clear segments** based on their behavior.
- These segments can help businesses:
  - Target high-spenders
  - Engage price-sensitive customers
  - Personalize marketing strategies

---

## 📚 Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
