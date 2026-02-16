# Task-3
# 📊 Task 3: Linear Regression — AI & ML Internship

---

## 📌 Task Objective

The objective of this task is to implement and understand **Simple and Multiple Linear Regression** using Python libraries such as **Scikit-learn, Pandas, and Matplotlib**.

This project demonstrates how machine learning can be used to **predict continuous values** (e.g., house prices) based on multiple input features.

---

## 🧠 Concepts Covered

* Data Preprocessing
* Train-Test Split
* Linear Regression Modeling
* Model Evaluation (MAE, MSE, R² Score)
* Data Visualization
* Interpretation of Model Coefficients

---

## 📂 Dataset Used

A sample **House Price Prediction Dataset** (`house_prices.csv`) is used.

### Features:

* `area` → Size of the house (sqft)
* `bedrooms` → Number of bedrooms
* `bathrooms` → Number of bathrooms
* `age` → Age of the house (years)

### Target Variable:

* `price` → House price value

---

## ⚙️ Tools & Technologies

* Python 🐍
* Pandas (Data Handling)
* NumPy (Numerical Computation)
* Scikit-learn (Machine Learning)
* Matplotlib (Visualization)

---

## 🏗️ Project Workflow

### 1️⃣ Import & Load Dataset

Dataset is loaded using Pandas and checked for missing values.

### 2️⃣ Data Preprocessing

* Removed null values (if any)
* Selected input features and target variable.

### 3️⃣ Train-Test Split

Dataset divided into:

* **80% Training Data**
* **20% Testing Data**

### 4️⃣ Model Training

A Linear Regression model is trained using:

```
sklearn.linear_model.LinearRegression
```

### 5️⃣ Prediction

The model predicts values based on unseen test data.

### 6️⃣ Model Evaluation

Performance measured using:

* **MAE (Mean Absolute Error)** → Average prediction error
* **MSE (Mean Squared Error)** → Penalizes large errors
* **R² Score** → Indicates how well the model fits the data

### 7️⃣ Visualization

* Scatter plot of **Actual vs Predicted Values**
* Regression relationship between feature (`area`) and target (`price`)

---

## 📈 Results Interpretation

* Positive coefficients indicate features that **increase the predicted value**.
* Larger area and more rooms generally lead to **higher predicted prices**.
* Evaluation metrics help measure model accuracy and reliability.

---


## 📚 Learning Outcome

This task provides a foundational understanding of:

* Regression-based predictive modeling
* Evaluating machine learning models
* Visualizing and interpreting results
* Applying supervised learning to real-world problems

---

## ✅ Conclusion

This project successfully demonstrates the implementation of **Linear Regression** for predictive analysis using Python.
It builds essential machine learning knowledge that can be extended to forecasting, analytics, and intelligent decision-making systems.

---

⭐ *Task Completed Successfully*

