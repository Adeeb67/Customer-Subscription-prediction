<!-- ========================================================= -->
<!--                     PROJECT HEADER                        -->
<!-- ========================================================= -->

<h1 align="center">📊 Customer Subscription Prediction</h1>

<p align="center">
Machine Learning analysis of bank marketing data to predict term deposit subscriptions
and identify key factors influencing customer decisions.
</p>

<p align="center">

![Status](https://img.shields.io/badge/status-completed-success)
![Python](https://img.shields.io/badge/python-3.9+-blue)
![Machine Learning](https://img.shields.io/badge/domain-Machine%20Learning-purple)
![Type](https://img.shields.io/badge/type-Predictive%20Modeling-green)
![Notebook](https://img.shields.io/badge/workflow-Jupyter%20Notebook-orange)
![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen)

</p>

---

## 📌 Project Overview

**Customer Subscription Prediction** is a Machine Learning project that analyzes
the **bankmarketing.csv** dataset to predict whether customers will subscribe
to a term deposit offered through bank marketing campaigns.

The project applies data preprocessing, encoding techniques, and multiple
classification models to extract insights and improve marketing strategies.

---

## 🎯 Project Objective

- Predict term deposit subscription outcomes
- Compare multiple machine learning models
- Identify key factors influencing customer decisions
- Generate actionable business insights

---

## 📂 Dataset

**bankmarketing.csv**

The dataset contains customer demographics and campaign interaction details.

Key attributes include:

- Age
- Job
- Marital Status
- Education
- Contact Type
- Month of Contact
- Call Duration
- Previous Campaign Outcome (poutcome)
- Subscription Result (Yes/No)

---

## 🧹 Data Preprocessing

- Data cleaning
- Encoding categorical variables
- Feature preparation
- Train-test split for modeling

---

## 🤖 Machine Learning Models Used

### Logistic Regression
- Baseline classification model
- Interpretable predictions

### Decision Tree
- Captures nonlinear relationships
- Easy visualization of decisions

### Random Forest ✅ (Best Performer)
- Ensemble learning approach
- Higher prediction accuracy
- Better generalization

---

## 🔑 Key Findings

Important features influencing subscription:

- 📞 Contact type
- 🔁 Previous campaign outcome (poutcome)
- 📅 Month of contact
- ⏱️ Call duration

These insights help optimize marketing strategies and customer targeting.

---

## 📁 Repository Structure

```
Customer-Subscription-prediction/
│
├── Bank_Term_Deposit_Summary.ipynb   # Analysis & model training
├── bankmarketing.csv                 # Dataset
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Adeeb67/Customer-Subscription-prediction.git
```

Move into project folder:

```bash
cd Customer-Subscription-prediction
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ How to Run

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Bank_Term_Deposit_Summary.ipynb
```

Run all cells to reproduce analysis and model results.

---

## 📊 Outputs

- Model performance comparison
- Feature importance insights
- Prediction evaluation metrics
- Visualization plots

---

## 🎓 Learning Outcomes

This project demonstrates:

- End-to-end Machine Learning workflow
- Data preprocessing & encoding
- Classification modeling
- Model comparison
- Business-focused ML interpretation

---

## 👨‍💻 Developer

**Mohammed Adeeb**

Computer Science & Data Analytics Student  
Building real-world Machine Learning and Analytics projects.

---

## ⭐ Support

If you like this project:

⭐ Star the repository  
🍴 Fork it  
📢 Share feedback  

---

<p align="center">
Built with 💻 + 🤖 by Mohammed Adeeb
</p>
