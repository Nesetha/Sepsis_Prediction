# Early Sepsis Warning & Clinical Risk Analytics Platform

## Overview

Early detection of sepsis is critical in intensive care units (ICUs), as delayed intervention can lead to severe complications, organ failure, and increased mortality. This project leverages healthcare analytics and machine learning to identify patients at risk of developing sepsis using ICU monitoring data.

Using the PhysioNet Sepsis Challenge dataset, a predictive analytics pipeline was developed to analyze patient vitals, generate risk scores, and support clinical decision-making through an interactive Tableau dashboard.

---

## Objectives

* Identify key clinical factors associated with sepsis.
* Develop a machine learning model for early sepsis risk prediction.
* Stratify patients into Low, Medium, and High-Risk categories.
* Build an interactive dashboard for healthcare monitoring and decision support.

---

## Dataset

**Source:** PhysioNet Sepsis Challenge Dataset

### Data Characteristics

* 1.55M+ ICU patient-hour observations
* 45K+ patient records
* Clinical variables including:

  * Heart Rate (HR)
  * Oxygen Saturation (O2Sat)
  * Temperature (Temp)
  * Respiratory Rate (Resp)
  * Blood Pressure (SBP, DBP, MAP)
  * Age
  * ICU Length of Stay (ICULOS)
  * Hospital Admission Time

---

## Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**
* **Tableau**

---

## Methodology

### Data Preparation

* Combined patient-level PSV files from PhysioNet datasets.
* Handled missing values using median imputation.
* Removed highly sparse variables.
* Performed exploratory data analysis and feature engineering.

### Machine Learning

* Random Forest Classifier
* Train-Test Split
* Model Evaluation using ROC-AUC

### Risk Scoring

Generated patient risk scores and categorized patients into:

* Low Risk
* Medium Risk
* High Risk

---

## Results

### Model Performance

* **ROC-AUC Score:** 0.944

### Key Risk Factors

1. Age
2. ICU Length of Stay (ICULOS)
3. Hospital Admission Time
4. Heart Rate (HR)
5. Systolic Blood Pressure (SBP)
6. Mean Arterial Pressure (MAP)
7. Respiratory Rate (Resp)
8. Diastolic Blood Pressure (DBP)
9. Oxygen Saturation (O2Sat)
10. Temperature (Temp)

---

## Dashboard Features

* Total Patient Monitoring Overview
* Sepsis Prevalence Analysis
* Risk Level Distribution
* Vital Sign Monitoring
* Top Clinical Risk Factors
* Patient Risk Stratification
* Actionable Clinical Insights

---

## Business Impact

This solution demonstrates how healthcare analytics can support:

* Early identification of high-risk patients
* Improved patient prioritization
* Clinical decision support
* Risk-based monitoring strategies
* Data-driven healthcare operations


## Author

Nesetha J C

Data Analytics | Business Analytics | Healthcare Analytics
