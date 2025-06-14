# 🏠 Housing Price Prediction with Ridge & Polynomial Regression

This project builds a **machine learning pipeline** to predict housing prices using data preprocessing, feature engineering, Ridge regression, and Polynomial regression techniques. The pipeline includes **scaling, encoding, model tuning, and evaluation** — a real-world workflow for production-grade ML models.

---

## 📌 Key Highlights

- ✅ Data Preprocessing with Scikit-learn Pipelines
- ✅ One-Hot Encoding of Categorical Features
- ✅ Feature Scaling (StandardScaler)
- ✅ Regression Models: Ridge, Polynomial + Ridge, and Linear
- ✅ Hyperparameter tuning using GridSearchCV
- ✅ Evaluation with RMSE, MAE, R²
- ✅ Visualization of Predicted vs Actual Housing Prices

---

## 📁 Project Structure

| File Name                     | Description                                          |
|------------------------------|------------------------------------------------------|
| `ridge_polynomial_pipeline.py`| Full modeling pipeline with hyperparameter tuning   |
| `housing.csv`                | Housing dataset (California Housing Data or similar)|
| `README.md`                  | Project overview                                     |

---

## 🔢 Dataset Features

The dataset includes housing-related information:

- `longitude`, `latitude`: Geolocation of the house
- `housing_median_age`, `median_income`: Demographics
- `ocean_proximity`: Categorical feature for location
- `median_house_value`: **Target variable**

---

## 🧪 Models Implemented

### 1. **Ridge Regression**
- Regularized linear model
- Prevents overfitting
- Grid search over `alpha` values

### 2. **Polynomial Regression + Ridge**
- Captures non-linear relationships
- Grid search over `degree` and `alpha`

### 3. **Linear Regression with Polynomial Features**
- Baseline comparison for model performance

---

## 📊 Performance Metrics

Each model was evaluated using:

- ✅ **RMSE** – Root Mean Squared Error  
- ✅ **MAE** – Mean Absolute Error  
- ✅ **R² Score** – Coefficient of Determination

> **Sample Output (Polynomial Ridge Regression):**
