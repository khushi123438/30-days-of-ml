# 🚀 Day 28 - SmartCart Customer Segmentation System (Part 1)

## 📌 Overview

Today, I started working on the **SmartCart Customer Segmentation System**, an unsupervised machine learning project designed to identify different customer groups based on their purchasing behavior, engagement levels, and loyalty indicators.

The objective is to help SmartCart improve personalized marketing, customer retention, and business decision-making through data-driven customer segmentation.

---

## 🎯 Problem Statement

SmartCart currently applies generic marketing strategies to all customers, making it difficult to identify high-value customers and users at risk of churn.

To address this challenge, customer transaction and engagement data will be analyzed using clustering techniques to discover hidden customer segments.

---

## 📊 Dataset Information

* Total Records: 2240 Customers
* Features: 22
* Data Categories:

  * Customer Demographics
  * Purchase Behavior
  * Purchase Frequency
  * Customer Engagement
  * Feedback & Complaints

### Important Features

* Income
* Recency
* MntWines
* MntFruits
* MntMeatProducts
* NumWebPurchases
* NumCatalogPurchases
* NumStorePurchases
* NumWebVisitsMonth
* Complain

---

## ✅ Tasks Completed

### 1. Data Understanding

* Explored dataset structure
* Identified numerical and categorical features
* Examined customer behavior variables

### 2. Data Cleaning

* Checked missing values
* Removed inconsistencies
* Handled outliers where necessary

### 3. Feature Engineering

* Created Total Spending feature
* Derived customer engagement indicators
* Prepared data for clustering

### 4. Exploratory Data Analysis (EDA)

* Analyzed customer income distribution
* Studied spending patterns across product categories
* Investigated purchase frequency trends
* Examined customer engagement behavior

### 5. Data Preprocessing

* Feature scaling using StandardScaler
* Selection of relevant clustering features
* Prepared final dataset for model training

---

## 📈 Key Insights

* Customer spending varies significantly across categories.
* Income appears to influence purchasing behavior.
* Some customers show high engagement while others remain inactive.
* Distinct behavioral patterns are visible and suitable for clustering analysis.

---

## 🔜 Next Steps

In Part 2, I will:

* Apply K-Means Clustering
* Use Elbow Method for optimal cluster selection
* Evaluate clusters using Silhouette Score
* Visualize customer segments
* Generate business recommendations

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

### Day 28 Progress

✔ Dataset Exploration
✔ Data Cleaning
✔ Feature Engineering
✔ Exploratory Data Analysis
✔ Data Scaling & Preparation

🚀 Ready for Clustering Implementation in Day 29.
