# Explainable AI (XAI) and Model Interpretability Analysis

A comprehensive machine learning and Explainable AI (XAI) project focused on understanding model behavior, feature relevance, and prediction interpretability using multiple feature selection methods, model-specific explanations, and SHAP-based analysis.

---

# Project Overview

This project investigates how different machine learning models make predictions and how individual features influence decision-making processes.

The analysis was conducted using two real-world domains:

* Loan Approval Prediction (Finance)
* Heart Disease Prediction (Healthcare)

The project applies multiple Explainable AI techniques to improve transparency, interpretability, and trustworthiness of machine learning systems.

---

# Objectives

* Perform feature relevance and feature selection analysis
* Compare Filter, Wrapper, and Embedded feature selection methods
* Analyze model-specific feature importance
* Apply model-agnostic Explainable AI using SHAP
* Compare interpretability results across multiple methods
* Understand consistency and differences between explanations

---

# Datasets Used

## 1. Loan Approval Dataset

Domain: Finance

Target Variable:

* `Loan_Approved`

Features include:

* Age
* Income
* Credit Score
* Loan Amount
* Loan Term
* Employment Status

---

## 2. Heart Disease Dataset

Domain: Healthcare

Target Variable:

* `num` 

Features include:

* Age
* Sex
* Chest Pain Type
* Cholesterol
* Blood Pressure
* Maximum Heart Rate
* Exercise Induced Angina
* Thalassemia
* And more medical indicators

---

# Explainable AI Techniques Used

## Feature Selection Methods

### 1. Filter Method

* Mutual Information
* Correlation Analysis

### 2. Wrapper Method

* Recursive Feature Elimination (RFE)

### 3. Embedded Method

* Random Forest Feature Importance

---

# Machine Learning Models

The following models were trained and evaluated:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

---

# Explainable AI (XAI)

The project uses SHAP (SHapley Additive exPlanations) for both global and local interpretability.

Implemented SHAP visualizations include:

* SHAP Summary Plot(loan_prediction_dataset)
<img width="768" height="380" alt="download" src="https://github.com/user-attachments/assets/72142c39-15db-4f3a-b19d-c8f492a22a1d" />

* SHAP Summary Plot(heart_disease_uci)
<img width="866" height="680" alt="image" src="https://github.com/user-attachments/assets/671a0762-e22f-4891-af4e-3f85c216b2e1" />
 
 
* SHAP Bar Plot(loan_prediction_dataset)
<img width="790" height="380" alt="download (2)" src="https://github.com/user-attachments/assets/edf4b5a3-4251-4802-9cd6-bc21220b8d7f" />

* SHAP Bar Plot(heart_disease_uci)
<img width="790" height="740" alt="image" src="https://github.com/user-attachments/assets/83a46871-0512-492f-8961-1a5555c55fb3" />


* SHAP Dependence Plot(loan_prediction_dataset)
<img width="657" height="453" alt="image" src="https://github.com/user-attachments/assets/039c7846-5b9f-4322-a6eb-40d004a571f7" />

* SHAP Dependence Plot(heart_disease_uci)
<img width="694" height="459" alt="image" src="https://github.com/user-attachments/assets/363d23ab-e649-4fb5-ab3d-229914867e17" />

 
* SHAP Force Plot
* SHAP Waterfall Plot

---

# Evaluation Techniques

The following evaluation metrics and visualizations were used:

* Accuracy Score
* Classification Report
* Confusion Matrix
* ROC Curve
* AUC Score

---

# Project Structure

```text
├── loan_approval_xai_analysis.ipynb
├── heart_disease_xai_analysis.ipynb
├── datasets/
│   ├── loan_prediction_dataset.csv
│   └── heart_disease_uci.csv
└── README.md
```

---

# Key Findings

## Loan Approval Dataset

* Credit Score was consistently identified as the most influential feature.
* Loan Amount and Income also showed strong predictive importance.
* SHAP explanations aligned closely with model-specific feature importance results.

---

## Heart Disease Dataset

* Medical features such as cholesterol, chest pain type, and maximum heart rate significantly influenced predictions.
* SHAP analysis revealed strong local and global interpretability patterns.
* Tree-based models effectively captured nonlinear medical relationships.

---

# Comparative Analysis

The project compares:

* Feature relevance across Filter, Wrapper, and Embedded methods
* Random Forest importance vs SHAP explanations
* Global interpretability vs local interpretability

The analysis demonstrated strong consistency between multiple interpretability techniques.

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* SHAP
* Google Colab

---

# Installation

Clone the repository:

```bash
[git clone https://github.com/Yeabebe/explainable-ai.git]
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Running the Project

Open the notebooks using:

* Jupyter Notebook
* Google Colab

Run all cells sequentially.

---

# Research and Learning Outcomes

This project enhanced understanding of:

* Explainable AI (XAI)
* Feature relevance analysis
* Model interpretability
* Global and local explanations
* Financial AI transparency
* Healthcare AI interpretability

---

# Future Improvements

Possible future enhancements include:

* LIME-based explanations
* Deep Learning interpretability
* Counterfactual explanations
* Fairness and bias analysis
* Explainable ensemble systems
* Interactive XAI dashboards

---

# Author

Yeabsera Abebe

Electrical and Computer Engineer | AI Engineer | Business Developer | Full-Stack Developer


---

# License

This project is for educational and research purposes.
