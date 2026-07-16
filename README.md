# 📈 Polynomial Logistic Regression Using Machine Learning

## 📌 Project Overview

This project demonstrates how to solve **non-linearly separable classification problems** using **Polynomial Logistic Regression**.

Unlike standard Logistic Regression, which creates a **linear decision boundary**, Polynomial Logistic Regression transforms the original features into higher-dimensional polynomial features, enabling the model to learn complex, curved decision boundaries.

The project uses the **ushape.csv** dataset to classify data that cannot be separated using a straight line, making it an excellent example of feature engineering and non-linear classification.

---

## 🎯 Objectives

- Understand the limitations of Linear Logistic Regression
- Learn Polynomial Feature Engineering
- Transform non-linear data into a higher-dimensional space
- Train a Polynomial Logistic Regression model
- Visualize non-linear decision boundaries
- Evaluate classification performance

---

## 📂 Dataset

**Dataset Used:** `ushape.csv`

The dataset contains two input features forming a **U-shaped distribution**, making it impossible for a simple linear classifier to separate the classes correctly.

### Features

- Feature 1 (X1)
- Feature 2 (X2)

### Target Variable

- Binary Class (0 / 1)

---

## 📖 Concepts Covered

- Binary Classification
- Logistic Regression
- Polynomial Feature Transformation
- Feature Engineering
- Non-Linear Decision Boundary
- Decision Boundary Visualization
- Model Training
- Model Evaluation
- Classification Metrics
- Overfitting vs Underfitting

---

## 🛠️ Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

---

## ⚙️ Implementation Steps

### Data Loading

- Load the U-Shape dataset
- Explore dataset structure
- Visualize class distribution

### Data Preprocessing

- Prepare input features
- Split dataset into training and testing sets

### Polynomial Feature Engineering

- Generate polynomial features using **PolynomialFeatures**
- Transform original feature space into higher dimensions

### Model Training

- Train Logistic Regression on transformed features
- Learn non-linear decision boundaries

### Model Evaluation

- Calculate Accuracy Score
- Generate Classification Report
- Evaluate prediction performance

### Visualization

- Plot original dataset
- Visualize polynomial decision boundary
- Compare linear vs polynomial classification

---

## 🔍 Key Observations

- Standard Logistic Regression struggles with non-linearly separable datasets.
- Polynomial Feature Engineering transforms the data into a space where Logistic Regression performs much better.
- Choosing an appropriate polynomial degree is important to balance model complexity and generalization.
- Feature engineering can significantly improve the performance of simple machine learning models.

---

## ✅ Advantages

- Demonstrates non-linear classification using Logistic Regression
- Easy to understand feature engineering concepts
- Visual explanation of decision boundaries
- Beginner-friendly implementation
- Excellent project for learning polynomial transformations

---

## 💻 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

---

## 🏁 Conclusion

This project shows how **Polynomial Logistic Regression** extends the capabilities of standard Logistic Regression by introducing polynomial features. By transforming the feature space, the model successfully learns complex decision boundaries and accurately classifies non-linearly separable data, making it a valuable technique for many real-world classification problems.
