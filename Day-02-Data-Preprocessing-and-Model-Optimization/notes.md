# 🚀 Day 2 - Data Preprocessing & Model Optimization

## 📘 Feature Engineering & Encoding

Feature Engineering is the process of creating, transforming, or selecting useful features from raw data to improve Machine Learning model performance.

Machine Learning models work with numerical data, so categorical values often need to be converted into numerical form.

### Common Encoding Techniques

#### Label Encoding

Converts categories into numerical labels.

Examples:
- Male → 0
- Female → 1

---

#### One-Hot Encoding

Creates separate binary columns for each category.

Examples:
- Color_Red
- Color_Blue
- Color_Green

---

## ⚠️ Dummy Variable Trap

The Dummy Variable Trap occurs when one encoded variable can be predicted using other variables, causing multicollinearity.

To avoid this:
- Remove one dummy column
- Use:
```python
drop_first=True
```

---

## 📉 Overfitting vs Underfitting

### 📌 Overfitting

Overfitting happens when the model learns the training data too well and performs poorly on new unseen data.

Characteristics:
- High training accuracy
- Low testing accuracy

Examples:
- Very complex models
- Memorizing training data

---

### 📌 Underfitting

Underfitting happens when the model fails to learn important patterns from the data.

Characteristics:
- Poor performance on training data
- Poor performance on testing data

Examples:
- Very simple models
- Insufficient training

---

## 🛡️ Regularization

Regularization is used to reduce overfitting by penalizing large model coefficients.

---

## 📌 Lasso Regression

Lasso Regression uses L1 regularization.

Advantages:
- Reduces overfitting
- Performs feature selection
- Can shrink coefficients to zero

---

## 📌 Ridge Regression

Ridge Regression uses L2 regularization.

Advantages:
- Reduces overfitting
- Keeps all features
- Prevents large coefficients

---

## 📌 ElasticNet

ElasticNet combines:
- Lasso Regression
- Ridge Regression

It balances feature selection and coefficient shrinking.

---

## 🤖 Logistic Regression

Logistic Regression is used for classification problems.

It predicts probabilities and class labels.

Examples:
- Spam detection
- Fraud detection
- Disease prediction

---

## 💡 Key Understanding

Machine Learning is not just about choosing an algorithm. Instead, good features, preprocessing, and proper tuning play a huge role in model performance.

---

## ✅ Topics Covered Today

- Feature Engineering & Encoding
- Dummy Variable Trap
- Overfitting & Underfitting
- Regularization
  - Lasso Regression
  - Ridge Regression
- ElasticNet Overview
- Logistic Regression

---

Excited to continue the #30DaysOfML journey 🚀
