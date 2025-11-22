# Ecommerce-Customer-Spend-Analysis
End-to-end machine learning project where I predict customer yearly spending and uncover the strongest revenue drivers using Linear Regression, EDA, and data visualization. High accuracy and clear business insights included.


---

### Predicting Yearly Customer Spend Using Linear Regression

---

## 📁 Project Overview

This project explores an E-Commerce customer dataset to understand what factors influence **Yearly Amount Spent** and to build a predictive model using **Linear Regression**.
The analysis covers the full data science workflow — from exploratory data analysis (EDA) to modeling, evaluation, and business insights.
It serves as a strong portfolio project demonstrating skills in Python, data analytics, and machine learning.

---

## 🔍 Objectives

* Identify key drivers of yearly customer spending
* Perform comprehensive **EDA** to understand relationships between variables
* Build and evaluate a **Linear Regression** model
* Interpret coefficients to generate **actionable business insights**
* Present clear conclusions that support data-driven decision making

---

## 📂 Dataset

The dataset includes customer behavioral and demographic information such as:

* Avg. Session Length
* Time on App
* Time on Website
* Length of Membership
* Yearly Amount Spent (target variable)



---

## 🧠 Key Steps in the Analysis

### **1. Exploratory Data Analysis (EDA)**

* Inspected dataset structure and summary stats
* Visualized relationships and correlations
* Identified strong positive correlations with:

  * **Length of Membership**
  * **Time on App**
* Found weak correlation with:

  * **Time on Website**

### **2. Feature Selection**

Selected the following predictors:

* Avg. Session Length
* Time on App
* Time on Website
* Length of Membership

### **3. Model Development — Linear Regression**

* Train/test split of 75/25
* Fitted a linear regression model using scikit-learn
* Evaluated model performance on test data

### **4. Model Evaluation Metrics**

* **R² Score:** 0.98 — model explains ~98% of variance
* **RMSE:** ~10.28 — average prediction error
* **Coefficient analysis** showed:

  * **Length of Membership** and **Time on App** are the strongest predictors
  * **Time on Website** has minimal impact

---

## 📈 Results Summary

✔ Customers who stay longer with the company spend **significantly more** each year
✔ Higher **mobile app engagement** is strongly linked to increased spending
✔ **Avg. Session Length** has a moderate positive effect
✔ **Time on Website** contributes very little to spend prediction

---

## 🧭 Business Insights

Based on the model and EDA:

* Improving **customer retention** should be a top priority
* Investing in **mobile app experience** yields higher ROI
* Website improvements may not drive spending as much as expected
* Long-term loyalty and app engagement are key drivers of revenue

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* scikit-learn
* Matplotlib / Seaborn
* Jupyter Notebook

---

## 🚀 Future Enhancements

* Add regularized models (Ridge, Lasso)
* Build interaction terms
* Deploy a simple web app for predictions
* Create a dashboard in Power BI or Tableau

---

## 🙌 About This Project

This project demonstrates the complete workflow of a data analyst/data scientist — from exploration to modeling to actionable insight generation. It is designed to show strong analytical thinking, technical capability, and communication skills.
Feel free to explore, fork, or reach out with suggestions!


