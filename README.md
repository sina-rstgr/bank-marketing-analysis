# Bank Marketing Analysis

## Project Description

This project presents an end-to-end data analysis and machine learning workflow based on the **Bank Marketing Dataset**.

The dataset contains **41,188 records** and **20 input attributes**, including client information, campaign-related features, and social and economic indicators. The target variable (`y`) indicates whether a client subscribed to a bank term deposit.

The project covers:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Predictive Modeling
- Model Evaluation and Comparison

Several classification algorithms were implemented and evaluated, including:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest

Hyperparameter tuning and preprocessing pipelines were also applied using `GridSearchCV` and Scikit-learn pipelines.

The data preparation process included SQL Server for initial data cleaning and Python/Pandas for further analysis and modeling.

---

## Dataset

The project uses the publicly available **Bank Marketing Dataset with social and economic context**, developed by Sérgio Moro, Paulo Cortez, and Paulo Rita.

The dataset includes client characteristics, campaign information, previous campaign outcomes, and social/economic indicators.

The raw dataset is not included in this repository.

### Dataset Reference

Moro, S., Cortez, P., & Rita, P. (2014).  
*A Data-Driven Approach to Predict the Success of Bank Telemarketing.*  
Decision Support Systems.  
DOI: 10.1016/j.dss.2014.03.001

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SQL Server
- SQLAlchemy
- Jupyter Notebook

---

## Repository Structure

```text
bank-marketing-analysis/
├── README.md
├── notebooks/
│   └── bank_marketing_analysis.ipynb
└── figures/
    ├── ...
    └── ...
