# Credit Scoring with Machine Learning and Uncertainty Estimation

## 📌 Overview
This project builds a **credit scoring system** that predicts loan default risk using machine learning, while incorporating **uncertainty estimation** and a **human-in-the-loop approach** for safer decision-making.  
It is based on the **German Credit Dataset (numeric version)** and demonstrates both predictive performance and decision reliability.

---

## Dataset
- **Name:** German Credit Data (numeric version)  
- **Features:** 20 numeric borrower characteristics  
- **Target:** `1` = Default, `0` = Non-default  

---

## Features
- **Multiple Models:** Logistic Regression, Decision Tree, Random Forest, XGBoost  
- **Best Model:** XGBoost with **88.4% Accuracy** and **0.92 ROC-AUC**  
- **Uncertainty Estimation:** Deep Ensembles & Monte Carlo Dropout  
- **Rejection Mechanism:** Defers high-uncertainty cases to human analysts  
- **Model Interpretability:** SHAP values to identify key predictors (repayment history, income, age)  

---

## Project Structure
├── Credit_Scoring.ipynb # Main Jupyter Notebook

├── german.data-numeric.csv # Dataset

├── README.md # Project documentation

└── Credit_Scoring_Report.pdf # Project report

## Usage
Open Credit_Scoring.ipynb in Jupyter Notebook or JupyterLab

Run the cells to:

Preprocess the data

Train multiple models

Evaluate performance

Visualize feature importance and uncertainty

## Results
Accuracy: 88.4%

ROC-AUC: 0.92

Top Features: Repayment history, income, age

Risk Control: Coverage–Risk analysis shows optimal balance at ~50% automation

## License
This project is licensed under the MIT License – see the LICENSE file for details.

## Contact
For inquiries, reach out at [Linkedin](https://www.linkedin.com/in/arunabiz/)
