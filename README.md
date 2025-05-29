# AIML-TASK-3-Linear-Regression-

# 🏠 House Price Prediction using Linear Regression

## 📌 Objective
This project is part of the **AI & ML Internship - Task 3**. The goal is to implement and understand **Linear Regression** (simple and multiple), evaluate its performance using error metrics, and visualize the model predictions to understand the relationship between housing features and price.

---

## 📂 Dataset
- **Dataset Used:** Housing Price Prediction Dataset
- **Source (Kaggle):** [Click here to view/download dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)

---

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Steps Performed

### 1. Data Preprocessing
- Loaded the dataset using `pandas`
- Inspected column types, null values, and descriptive statistics
- Selected relevant features and the target variable

### 2. Model Building
- Performed **Simple Linear Regression** using the `rm` feature
- Performed **Multiple Linear Regression** using `rm`, `lstat`, and `ptratio`

### 3. Model Training
- Used `train_test_split` to divide data (80% train, 20% test)
- Trained models using `LinearRegression()` from `sklearn.linear_model`

### 4. Model Evaluation
Evaluated both models using:
- **MAE**: Mean Absolute Error
- **MSE**: Mean Squared Error
- **R² Score**: Coefficient of Determination

### 5. Visualization
- Plotted regression line over actual data (Simple LR)
- Visualized predictions vs actual prices
- Displayed model coefficients and interpreted them

---

## 📈 Evaluation Results

| Model                     | MAE     | MSE     | R² Score |
|---------------------------|---------|---------|----------|
| Simple Linear Regression  | ~14.13  | ~36.1   | ~0.27    |
| Multiple Linear Regression| ~11.35  | ~22.3   | ~0.54    |


---

---

## ✅ Conclusion
This project demonstrates the use of linear regression in predicting house prices based on features like number of rooms and area statistics. It includes model training, evaluation, and visualization using widely-used Python tools.

---

## 📬 Submission
This repository has been submitted as part of **Task 3** of the AI & ML Internship.

---
Submitted by: MUMMADI RAMCHARAN


