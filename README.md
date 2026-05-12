# AI Job Market & Salary Intelligence Dashboard

## Overview

An end-to-end analytics and machine learning project analyzing global AI and data science salary trends, hiring patterns, remote work distribution, and key salary drivers using Python, Scikit-learn, and Power BI.

This project combines:

* Data cleaning and preprocessing
* Exploratory data analysis
* Machine learning-based salary prediction
* Feature importance analysis
* Interactive Power BI dashboards
* Business intelligence storytelling

The dashboard was designed to provide executive-level insights into the evolving AI and data science job market.

---

# Dashboard Features

## Executive Overview

* KPI cards for salary and hiring insights
* Average salary trends over time
* Global hiring distribution map
* Remote vs hybrid vs onsite analysis
* Salary decomposition analysis

## Salary Intelligence

* Top-paying AI/data roles
* Salary distribution analysis using box plots
* Remote work vs salary analysis
* Experience-level salary comparisons

## Job Market Intelligence

* AI role category breakdowns
* Heatmaps for salary patterns
* Company size and compensation analysis
* Hiring trends across job categories

## ML Prediction Insights

* Random Forest salary prediction model
* Predicted vs actual salary visualization
* Feature importance analysis
* Explainable AI insights

---

# Tech Stack

## Languages & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## BI & Visualization

* Power BI

## Machine Learning

* Random Forest Regressor

## Development Tools

* Jupyter Notebook
* VS Code

---

# Dataset

Dataset used:

* Data Science Job Salaries Dataset (Kaggle)

Dataset includes:

* Job titles
* Experience levels
* Employment type
* Company size
* Employee residence
* Company location
* Remote work ratio
* Salary in USD

---

# Machine Learning Pipeline

## Steps Performed

### Data Cleaning

* Removed duplicates
* Mapped categorical variables
* Created role categories
* Created work setting categories

### Feature Engineering

* Role categorization
* Remote work classification
* Salary band analysis

### Model Training

* Random Forest Regression
* Train-test split
* Feature importance extraction

### Model Evaluation

* MAE: ~28K
* R² Score: ~0.54

---

# Key Insights

* Employee residence is the strongest salary driver.
* Senior and executive roles command significantly higher salaries.
* Remote AI jobs remain highly competitive in compensation.
* Large companies dominate AI and data science hiring.
* Geographic location strongly impacts salary distribution.

---

# Power BI Visualizations Used

* KPI Cards
* Decomposition Tree
* Heatmap Matrix
* Scatter Plot
* Filled Map
* Donut Chart
* Treemap
* Box Plot
* Feature Importance Analysis

---

# Project Structure

```text
ai-job-market-intelligence-dashboard/
│
├── data/
│   ├── cleaned_jobs.csv
│   ├── salary_predictions.csv
│   ├── feature_importance.csv
│   └── ds_salaries.csv
│
├── notebooks/
│   └── main.ipynb
│
├── powerbi/
│   └── AI_Job_Market_Dashboard.pbix
│
├── screenshots/
│   ├── executive_overview.png
│   ├── salary_intelligence.png
│   ├── market_intelligence.png
│   └── ml_insights.png
│
├── requirements.txt
└── README.md
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/ai-job-market-intelligence-dashboard.git
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Requirements

```text
pandas
numpy
scikit-learn
matplotlib
```

---

# How to Run

1. Open the notebook inside:

```text
notebooks/main.ipynb
```

2. Run all notebook cells.

3. Export processed CSV files.

4. Open:

```text
powerbi/AI_Job_Market_Dashboard.pbix
```

5. Refresh Power BI data if needed.

---

---

# Future Improvements

* Deploy dashboard using Streamlit
* Integrate real-time job APIs
* Add NLP-based skill extraction
* Add salary forecasting models
* Build resume-job matching engine

---

# Bullet Points

* Built an AI Job Market & Salary Intelligence Dashboard using Python, Scikit-learn, and Power BI to analyze salary trends, remote work patterns, hiring insights, and ML-based salary prediction across AI/data science roles.

* Designed interactive dashboards featuring decomposition trees, heatmaps, feature importance analysis, KPI tracking, and global hiring visualizations for business intelligence storytelling.

---

# Author

Prerana Somani<br>
MS in Data Science<br>
Stony Brook University
