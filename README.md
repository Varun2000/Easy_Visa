# EasyVisa - Visa Approval Prediction

## Project Overview
This project builds a machine learning classification model to predict whether a US visa application is likely to be **Certified** or **Denied** based on employer and applicant information.

The goal is to help streamline the visa review process by identifying the factors that significantly influence visa approval outcomes and recommending suitable applicant profiles.

---

## Business Problem
Business communities in the United States face increasing demand for skilled human resources. One of the biggest challenges is identifying and attracting the right talent while remaining competitive.

Under the **Immigration and Nationality Act (INA)**, US employers can hire foreign workers on a temporary or permanent basis, provided they comply with regulations that protect US workers’ wages and working conditions. These applications are processed by the **Office of Foreign Labor Certification (OFLC)**.

In FY 2016 alone, OFLC processed:

- **775,979 employer applications**
- **1,699,957 positions**
- A **9% increase** from the previous year

As the number of applicants continues to grow, reviewing every case manually becomes increasingly difficult. This creates a strong need for a **machine learning-based solution** to support visa certification decisions.

---

## Objective
The objective of this project is to develop a classification model that can:

- Facilitate the visa approval process
- Predict whether a visa application will be **Certified** or **Denied**
- Identify the most important drivers behind visa approval decisions
- Recommend suitable applicant profiles with higher chances of visa certification

---

## Dataset Description
The dataset contains attributes related to both employees and employers.

### Features
- **case_id**: Unique ID of each visa application
- **continent**: Continent of the employee
- **education_of_employee**: Education level of the employee
- **has_job_experience**: Whether the employee has prior job experience (`Y`/`N`)
- **requires_job_training**: Whether the employee requires job training (`Y`/`N`)
- **no_of_employees**: Number of employees in the employer’s company
- **yr_of_estab**: Year in which the employer’s company was established
- **region_of_employment**: Intended region of employment in the US
- **prevailing_wage**: Average wage paid to similarly employed workers in the area
- **unit_of_wage**: Wage unit (`Hourly`, `Weekly`, `Monthly`, `Yearly`)
- **full_time_position**: Whether the position is full-time (`Y`/`N`)
- **case_status**: Target variable indicating visa outcome (`Certified` / `Denied`)

---

## Project Workflow
1. **Data Understanding**
   - Explore dataset structure
   - Understand feature meanings
   - Check target distribution

2. **Data Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Treat outliers if necessary
   - Feature engineering

3. **Exploratory Data Analysis**
   - Univariate and bivariate analysis
   - Identify patterns affecting visa approval
   - Visualize relationships between features and target

4. **Model Building**
   - Train classification models
   - Compare baseline and advanced models
   - Tune hyperparameters

5. **Model Evaluation**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC-AUC

6. **Insights and Recommendations**
   - Identify key factors influencing case status
   - Recommend applicant profiles with stronger approval potential

---

## Machine Learning Models
Some classification algorithms that can be used in this project include:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- XGBoost
- AdaBoost

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---
