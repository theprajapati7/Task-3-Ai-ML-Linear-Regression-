# 🏡 House Price Prediction using Linear Regression

## 📋 Project Overview
This project aims to predict house prices using **Simple** and **Multiple Linear Regression** models.  
We use a housing dataset with features like area, bedrooms, and bathrooms to train a predictive model.

---

## 🛠️ Tools and Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn (sklearn)
- Matplotlib

---

## 📈 Workflow

1. **Data Loading**  
   Load the dataset (`Housing.csv`) and check for missing values.

2. **Data Preprocessing**  
   Encode categorical features using one-hot encoding.

3. **Feature Selection**  
   Selected features like `area`, `bedrooms`, and `bathrooms` for the model.

4. **Train-Test Split**  
   Split the dataset into 80% training and 20% testing.

5. **Model Training**  
   Trained a **Linear Regression** model using `sklearn.linear_model.LinearRegression`.

6. **Model Evaluation**  
   Evaluated the model performance using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score

7. **Visualization**  
   Plotted **Actual vs Predicted** house prices to visually analyze model performance.

8. **Interpretation**  
   Displayed model coefficients and intercept to understand the relationship between features and the target variable.

