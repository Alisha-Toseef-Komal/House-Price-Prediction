
# 🏡 House Price Prediction

## 🎯 Task Objective
To build a machine learning model that predicts house prices based on property features such as square footage, number of bedrooms, and location. This task is part of the AI/ML Engineering Internship at DevelopersHub Corporation.

---

## 📂 Dataset Used
- **File**: `housing.csv`
- **Description**: Real estate dataset containing various features such as:
  - `area` (in square feet)
  - `bedrooms`
  - `bathrooms`
  - `location`
  - `price` (target variable)
- **Source**: Provided as part of the internship materials

---

## 🔧 Steps Performed

### 1. Data Loading & Inspection
- Loaded the CSV file using `pandas`
- Explored shape, column names, and basic statistics
- Checked for missing values and data types

### 2. Data Preprocessing
- Handled missing values by dropping or imputing
- One-hot encoded categorical features like `location`
- Ensured numerical features were scaled if necessary

### 3. Model Building
- **Model Used**: Linear Regression
- Split the dataset into training and test sets
- Trained the model using `sklearn`

### 4. Model Evaluation
- Metrics used:
  - **MAE (Mean Absolute Error)**
  - **RMSE (Root Mean Squared Error)**
- Compared actual vs. predicted prices using scatter plots

### 5. Results Summary
- The model successfully captured trends in pricing based on square footage, bedrooms, and location.
- Room for improvement: try Gradient Boosting or cross-validation for higher accuracy.

---

## 📊 Key Results

| Metric | Value |
|--------|-------|
| MAE    | _129233.30_ |
| RMSE   | _214212.15_ |

*(Replace with actual values from your notebook)*

---

## 📁 Repository Structure

```
📦house-price-prediction
 ┣ 📜housing.csv
 ┣ 📓House_Price_Prediction.ipynb
 ┗ 📜README.md
```

---

## 🚀 Future Improvements
- Try Gradient Boosting, Random Forest, or XGBoost for better performance.
- Perform feature engineering on date or area trends.
- Apply grid search for hyperparameter tuning.


