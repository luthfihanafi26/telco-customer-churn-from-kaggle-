# Telco Customer Churn from Kaggle

## Project Overview
Customer churn is a critical issue in the telecommunications industry, where retaining existing customers is often more cost-effective than acquiring new ones.  
This project aims to explore customer behavior and build a machine learning model to predict customer churn using the **Telco Customer Churn** dataset from Kaggle.

The analysis focuses on understanding patterns, relationships, and factors associated with customer churn through **Exploratory Data Analysis (EDA)**, followed by data preprocessing and predictive modeling.

---

## Dataset
- **Source**: Kaggle – Telco Customer Churn Dataset  
- **Observations**: 7,043 customers  
- **Features**: 21 variables (demographic, service-related, and account information)  
- **Target variable**: `Churn` (Yes / No)

---

## Exploratory Data Analysis (EDA)
The EDA process is conducted to understand the structure and characteristics of the data before modeling.  
Key aspects explored include:
- Dataset structure, data types, and missing values
- Distribution of numerical variables such as `tenure`, `MonthlyCharges`, and `TotalCharges`
- Distribution of categorical variables (e.g., `Contract`, `InternetService`, `PaymentMethod`)
- Analysis of churn rate across different customer segments
- Exploration of relationships between customer attributes and churn (association-based, not causal)

The goal of EDA is to identify meaningful patterns and insights that can inform feature engineering and model selection.

---

## Data Preprocessing
The preprocessing steps include:
- Handling missing values
- Converting data types where necessary
- Encoding categorical variables
- Feature scaling for numerical variables
- Splitting the dataset into training and testing sets

These steps ensure the data is suitable for machine learning models.

---

## Modeling
Several classification models are applied to predict customer churn, including:
- Logistic Regression
- Decision Tree
- Random Forest *(if applicable)*

Model performance is evaluated using metrics such as:
- Accuracy
- Precision
- Recall
- F1-score

---

## Results
The results indicate that customer churn is strongly associated with:
- Contract type (month-to-month contracts show higher churn rates)
- Customer tenure
- Monthly charges
- Payment method

The final model demonstrates reasonable predictive performance and provides insights that could support customer retention strategies.

---

## Conclusion
This project demonstrates an end-to-end data science workflow, starting from exploratory analysis to predictive modeling.  
The findings highlight key customer characteristics associated with churn and show how data-driven approaches can help businesses better understand and anticipate customer behavior.

---

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## Author
Muhammad Luthfi Hanafi Putera
