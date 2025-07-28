# 🚗 Used Car Price Prediction

This project predicts the selling price of used cars using machine learning. It uses a real-world dataset and involves extensive preprocessing, feature engineering, and model training to create a robust regression model.

## 📌 Project Highlights

- Real-world regression problem
- Heavy data preprocessing
- Feature encoding
- Random Forest Regressor model
- Model persistence with `pickle`
- Input-based predictions for new data

---

## 📁 Dataset Description

The dataset contains the following features:

| Column           | Description                                       |
|------------------|---------------------------------------------------|
| Car_Name         | Name of the car                                   |
| Year             | Year the car was purchased                        |
| Selling_Price    | Price at which the car is being sold *(target)*   |
| Present_Price    | Current ex-showroom price of the car              |
| Kms_Driven       | Kilometers driven                                 |
| Fuel_Type        | Type of fuel used (Petrol, Diesel, etc.)          |
| Seller_Type      | Type of seller (Dealer/Individual)                |
| Transmission     | Manual or Automatic                               |
| Owner            | Number of previous owners                         |

---

## 🧪 Workflow

1. **Data Loading**  
   Read and explore the CSV dataset using pandas.

2. **Preprocessing**  
   - Converted categorical columns using one-hot encoding
   - Dropped unused features (like `Car_Name`)
   - Converted `Year` to car age

3. **Model Building**  
   - Train-test split
   - RandomForestRegressor was trained and evaluated
   - Accuracy measured using R² Score

4. **Model Evaluation**  
   - R² score close to 0.89+ indicating good performance

5. **Model Saving & Loading**  
   - Model saved using `pickle`
   - Test prediction done using loaded model

---

## 📊 Sample Output

```python
Predicted Selling Price: ₹5.43 Lakhs
