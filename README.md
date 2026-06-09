# employee-attrition-prediction
# Employee Attrition Prediction using Machine Learning

## Overview

This project was developed as part of **Talent Hack2K26** under the theme **Decision Intelligence & Business Impact**.

Employee attrition is a major challenge for organizations as it increases recruitment costs, training expenses, productivity loss, and workforce instability. This project uses Machine Learning and Data Analytics to identify employees who are at risk of leaving the organization and support data-driven HR decision-making.

---

## Problem Statement

Organizations face significant challenges due to employee attrition. Predicting employees who are likely to leave can help HR teams take proactive measures to improve retention and workforce planning.

---

## Objectives

* Analyze employee-related data to identify attrition patterns.
* Predict employee attrition using Machine Learning.
* Identify key factors influencing employee turnover.
* Support HR departments with actionable insights.
* Enable data-driven decision intelligence.

---

## Dataset

**Dataset:** IBM HR Analytics Employee Attrition Dataset

* Records: 1470 Employees
* Features: 35
* Target Variable: Attrition (Yes/No)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Excel
* Power BI

---

## Machine Learning Model

### Random Forest Classifier

The Random Forest algorithm was used to predict employee attrition based on employee demographics, salary, department information, employment status, and other HR-related attributes.

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

* Employee Attrition Distribution
* Gender Distribution Analysis
* Department-wise Employee Analysis
* Salary Distribution Analysis
* Department vs Attrition Analysis
* Salary vs Attrition Comparison

---

## Model Evaluation

Evaluation metrics used:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

Approximate Results:

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 87%   |
| Precision | 82%   |
| Recall    | 79%   |
| F1-Score  | 80%   |

---

## Risk Classification

Employees are categorized based on predicted attrition probability:

* High Risk (≥ 0.75)
* Medium Risk (0.50 – 0.74)
* Low Risk (< 0.50)

---

## Project Outputs

* Employee Attrition Prediction Model
* Feature Importance Analysis
* Confusion Matrix Visualization
* Excel Dashboard
* Power BI Dashboard
* Attrition Risk Assessment

---

## Repository Structure

```text
employee-attrition-prediction/
│
├── Dataset/
│   └── HRDataset_filled.xlsx
│
├── Notebook/
│   └── Employee_Attrition_Prediction.ipynb
│
├── PowerBI/
│   └── Employee_Attrition_Dashboard.pbix
│
├── PPT/
│   └── TalentHack2K26_Presentation.pptx
│
├── Images/
│   ├── excel_dashboard.png
│   ├── powerbi_dashboard.png
│   ├── confusion_matrix.png
│   └── feature_importance.png
│
├── requirements.txt
└── README.md
```

---

## Team Members

* Lohita Kandaswamy
* Nishanthini V
* Reshma R

---

## Hackathon

Talent Hack2K26

Theme: Decision Intelligence & Business Impact

Successfully cleared the first two individual rounds and advanced to the final round, where the team developed and presented the Employee Attrition Prediction solution.

---

## Acknowledgements

Special thanks to:

* Hyper Launch
* Naan Mudhalvan

for providing a platform to apply technology and analytics to solve real-world business problems.

---

## Future Enhancements

* Deploy as a web application.
* Integrate real-time HR data.
* Improve prediction accuracy using advanced ML models.
* Develop automated retention recommendation systems.
