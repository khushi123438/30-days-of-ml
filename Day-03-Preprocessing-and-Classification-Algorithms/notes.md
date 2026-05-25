# 🚀 Day 3 - Preprocessing, Evaluation Metrics & Classification Algorithms

## 📘 Standardization & Normalization

Data preprocessing is an important step in Machine Learning because different features may have different scales.

Scaling helps models perform better and train faster.

---

## 📌 Standardization

Standardization transforms data so that it has:
- Mean = 0
- Standard Deviation = 1

It is useful when data follows a normal distribution.

### Formula


::contentReference[oaicite:0]{index=0}


Where:
- x = data point
- μ = mean
- σ = standard deviation

---

## 📌 Normalization

Normalization scales values between 0 and 1.

It is useful when features have different ranges.

### Formula

:contentReference[oaicite:1]{index=1}

---

## ⚙️ StandardScaler

StandardScaler is a Scikit-learn tool used for standardization.

Example:
```python
from sklearn.preprocessing import StandardScaler

scaler = StandardScaler()

X_scaled = scaler.fit_transform(X)
```

---

## 📊 Confusion Matrix

A Confusion Matrix is used to evaluate classification models.

It shows:
- True Positive (TP)
- True Negative (TN)
- False Positive (FP)
- False Negative (FN)

It helps understand how well the model performs.

---

## 📈 Classification Evaluation Metrics

### 📌 Accuracy

Accuracy measures how many predictions are correct.

:contentReference[oaicite:2]{index=2}

---

### 📌 Precision

Precision measures how many predicted positives are actually correct.

:contentReference[oaicite:3]{index=3}

---

### 📌 Recall

Recall measures how many actual positives are correctly predicted.

:contentReference[oaicite:4]{index=4}

---

### 📌 F1 Score

F1 Score balances Precision and Recall.

:contentReference[oaicite:5]{index=5}

---

## 🤖 Naive Bayes Algorithm

Naive Bayes is a classification algorithm based on probability and Bayes’ Theorem.

It assumes that features are independent of each other.

Common Uses:
- Spam detection
- Sentiment analysis
- Text classification

---

## 📌 Types of Naive Bayes

### Gaussian Naive Bayes
Used for continuous numerical data.

### Multinomial Naive Bayes
Used for text and frequency-based data.

### Bernoulli Naive Bayes
Used for binary data.

---

## 🤝 k-Nearest Neighbours (kNN)

kNN is a supervised learning algorithm used for classification and regression.

It works by finding the nearest data points.

### Steps:
1. Choose value of K
2. Find nearest neighbours
3. Take majority vote

---

## ⚠️ Limitations of kNN

- Slow for large datasets
- Sensitive to noise
- Performance decreases with high-dimensional data

---

## 📘 Validation Data

Validation data is used to tune model performance before final testing.

It helps avoid overfitting.

---

## 🔁 Cross Validation

Cross Validation evaluates model performance using multiple data splits.

Commonly used:
- K-Fold Cross Validation

Benefits:
- Better model evaluation
- More reliable performance estimation

---

## ⚙️ Hyperparameter Tuning using CV

Hyperparameter tuning helps find the best parameters for a model.

Examples:
- Value of K in kNN
- Learning rate
- Regularization strength

Cross Validation is often used during tuning.

---

## 🔗 Pipeline in Scikit-learn

Pipeline helps combine preprocessing and model training steps together.

Benefits:
- Cleaner code
- Easier workflow
- Prevents data leakage

Example:
```python
from sklearn.pipeline import Pipeline
```

---

## 💡 Key Understanding

Machine Learning is not only about training models. Proper preprocessing, evaluation metrics, and validation techniques are equally important for building accurate and reliable models.

---

## ✅ Topics Covered Today

- Standardization & Normalization
- StandardScaler
- Confusion Matrix
- Classification Evaluation Metrics
- Naive Bayes Algorithm
- Types of Naive Bayes
- k-Nearest Neighbours (kNN)
- Limitations of kNN
- Validation Data
- Cross Validation
- Hyperparameter Tuning using CV
- Pipeline in Scikit-learn

---

Excited to continue the #30DaysOfML journey 🚀
