# Telecom Customer Churn Analysis

## Project Overview

Customer churn is a major challenge in the telecom industry. Retaining existing customers is significantly cheaper than acquiring new ones. This project performs Exploratory Data Analysis (EDA) and builds machine learning models to identify key factors contributing to customer churn.

The goal is to uncover insights that can help telecom companies reduce churn and improve customer retention.

---

## Dataset

The dataset contains customer information including:

- Demographics
- Contract details
- Services subscribed
- Monthly and total charges
- Churn status

Each row represents a telecom customer.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Cleaning
- Handled missing values
- Converted categorical variables
- Prepared dataset for analysis

### 2. Exploratory Data Analysis (EDA)

Analyzed relationships between churn and:

- Contract type
- Monthly charges
- Tenure
- Services subscribed

### 3. Data Visualization

Used visualization techniques to identify churn patterns:

- Count plots
- Heatmaps
- Distribution plots
- Correlation analysis

### 4. Model Building

Built machine learning models to predict customer churn:

- Logistic Regression
- Random Forest Classifier

### 5. Model Evaluation

Evaluated models using:

- Accuracy Score
- ROC AUC Score
- Confusion Matrix
- Classification Report

---

## Key Insights

- Customers with **month-to-month contracts** show the highest churn rate.
- Higher **monthly charges** correlate with increased churn.
- Customers without **technical support or online security** churn more frequently.
- **Tenure plays a critical role** in predicting customer retention.

---

## Project Structure

```
telecom-customer-churn-analysis
│
├── data
├── notebooks
├── images
├── README.md
└── requirements.txt
```

---

## How to Run the Project

Clone the repository:

```bash
git clone https://github.com/yourusername/telecom-customer-churn-analysis.git
```

Navigate to the project:

```bash
cd telecom-customer-churn-analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## Future Improvements

- Hyperparameter tuning
- Model deployment using Streamlit
- Interactive churn dashboard
- Feature importance analysis

---

## Author

Your Name  
Aspiring Data Analyst
