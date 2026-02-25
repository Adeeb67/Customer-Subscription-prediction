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
![Modeling](https://img.shields.io/badge/type-Predictive%20Modeling-green)
![Scikit-Learn](https://img.shields.io/badge/library-Scikit--Learn-orange)
![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen)

</p>

---

## 📌 Project Overview

**Customer Subscription Prediction** is a Machine Learning project that analyzes
the **bankmarketing.csv** dataset to predict whether customers will subscribe
to a term deposit offered through bank marketing campaigns.

The project combines data preprocessing, feature engineering, and supervised
learning models to uncover behavioral patterns and optimize marketing strategies.

---

## 🎯 Project Objective

- Predict customer subscription outcomes
- Identify influential marketing features
- Compare multiple machine learning models
- Improve campaign targeting efficiency
- Extract actionable business insights

---

## 📂 Dataset

The project uses:

**bankmarketing.csv**

The dataset includes customer demographics, campaign interactions,
and marketing outcomes.

Example features:

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

- Handled missing values
- Encoded categorical variables
- Feature transformation
- Data normalization where required
- Train-test split preparation

---

## 🤖 Machine Learning Models Used

### 1️⃣ Logistic Regression
- Baseline classification model
- Interpretable probability predictions

### 2️⃣ Decision Tree
- Captured nonlinear relationships
- Easy feature interpretation

### 3️⃣ Random Forest ✅
- Ensemble learning approach
- Reduced overfitting
- Best overall performance

---

## 📊 Model Results

After training and evaluation:

- **Random Forest achieved the best performance**
- Improved prediction stability
- Captured complex feature interactions

---

## 🔑 Key Insights

The most important factors influencing subscription:

- 📞 **Contact Type**
- 🔁 **Previous Campaign Outcome (poutcome)**
- 📅 **Month of Contact**
- ⏱️ **Call Duration**

These insights can help banks:

- Optimize campaign timing
- Improve customer targeting
- Increase subscription success rates

---

## 🧠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Machine Learning Classification

---

## 📁 Repository Structure

```
Customer-Subscription-prediction/
│
├── notebooks/
│   └── model training & analysis
│
├── datasets/
│   └── bankmarketing.csv
│
├── models/
│   └── trained model experiments
│
├── visuals/
│   └── plots and evaluation charts
│
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Adeeb67/Customer-Subscription-prediction.git
```

Navigate into project folder:

```bash
cd Customer-Subscription-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run all cells to reproduce the analysis and models.

---

## 📈 Outputs

- Trained classification models
- Model performance comparison
- Feature importance analysis
- Prediction insights
- Visualization charts

---

## 🎓 Learning Outcomes

This project demonstrates:

- End-to-end Machine Learning workflow
- Data preprocessing & encoding
- Classification modeling
- Model comparison techniques
- Business-oriented ML interpretation

---

## 👨‍💻 Developer

**Mohammed Adeeb**

Computer Science & Data Analytics Student  
Building real-world Machine Learning and Analytics projects.

---

## 🍴 How to Fork & Use

1. Click **Fork** (top-right of repository)
2. Clone your fork:

```bash
git clone https://github.com/<your-username>/Customer-Subscription-prediction.git
```

3. Create a new branch:

```bash
git checkout -b feature-name
```

4. Commit changes:

```bash
git commit -m "Added improvement"
```

5. Push changes:

```bash
git push origin feature-name
```

6. Open a Pull Request 🚀

---

## 🤝 Contributions

Contributions are welcome for:

- Model improvements
- Hyperparameter tuning
- Visualization enhancements
- Feature engineering ideas

Please open an issue before major changes.

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
