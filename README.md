# Telecom Customer Churn Prediction

**Author:** Hyndavi Bejjenki

## 📊 Project Overview

This project aims to **predict customer churn** in the telecom sector using **Logistic Regression**. Customer churn is a crucial business problem, as retaining existing customers is often more cost-effective than acquiring new ones. The goal is to analyze customer data, identify key factors contributing to churn, and build a predictive model to classify whether a customer is likely to churn.

---

## 📁 Table of Contents

- [Project Overview](#-project-overview)
- [Dataset Description](#-dataset-description)
- [Installation & Usage](#-installation--usage)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Model Building](#-model-building)
- [Key Results](#-key-results)
- [Conclusion & Future Work](#-conclusion--future-work)
- [License](#-license)
- [Contact](#-contact)

---

## 📂 Dataset Description

- **Source:** [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn) (Kaggle)
- **Features include:**
  - Customer demographics (gender, senior citizen, partner, dependents)
  - Account information (tenure, contract, payment method)
  - Service details (phone service, internet service, streaming services)
  - **Target variable:** `Churn` (Yes/No)

---
## ⚙️ Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/Hyndavi334/Telecom-Churn-Logistic-Regression.git
   cd Telecom-Churn-Logistic-Regression
   
2. **Create and activate virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # Mac/Linux
   venv\Scripts\activate      # Windows

3. **Install requirements**
   ```bash
   pip install -r requirements.txt

4. **Run Jupyter Notebooks**
    ```bash
    jupyter notebook
Open the notebooks under Notebooks/ folder to explore EDA and model training.

---
## 🔍 Exploratory Data Analysis

**Key EDA steps performed:**

- Missing value analysis and imputation
- Distribution plots for numerical features
- Count plots for categorical features
- Correlation heatmap to understand feature relationships

**Example plot:**

![Churn counts by Gender (Yes vs No)](Images/Churn%20counts%20by%20Gender%20(Yes%20vs%20No).png)
![Distribution of Monthly charges](Images/Distribution%20of%20Monthly%20charges.png)

---
## 🤖 Model Building

**Algorithm used:** Logistic Regression

**Preprocessing:** 
- Label Encoding for target variable
- One Hot Encoding for categorical features

**Evaluation metrics:** 
- Accuracy
- Confusion Matrix
- Classification Report

**Example Confusion Matrix:**


