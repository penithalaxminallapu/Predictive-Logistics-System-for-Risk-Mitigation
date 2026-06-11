# Predictive Logistics System for Risk Mitigation (Shipment Delay Prediction)

## Project Overview

Developed a Machine Learning-based logistics risk management system that predicts shipment delays and enables proactive intervention before delivery disruptions occur. The solution helps organizations optimize supply chain operations, improve delivery performance, and reduce revenue loss caused by delayed shipments.

## Problem Statement

Shipment delays can negatively impact customer satisfaction, operational efficiency, and business profitability. The objective of this project is to accurately identify high-risk shipments and provide actionable insights for mitigating delivery risks.

## Objectives

* Predict shipment delays using historical logistics data.
* Identify key factors contributing to delivery delays.
* Improve supply chain efficiency through predictive analytics.
* Enable proactive decision-making and risk mitigation.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* SMOTE
* GridSearchCV
* Matplotlib
* Seaborn
* Jupyter Notebook

## Methodology

1. Data Cleaning and Preprocessing
2. Missing Value Imputation
3. Feature Engineering
4. Class Imbalance Handling using SMOTE
5. Model Training using XGBoost
6. Hyperparameter Optimization using GridSearchCV
7. Feature Importance Analysis
8. Model Evaluation and Performance Assessment

## Model Performance

| Metric                     | Value  |
| -------------------------- | ------ |
| Accuracy                   | 67.59% |
| Recall (Delayed Shipments) | 98%    |
| Recall (On-Time Shipments) | 47%    |

The model prioritizes detecting delayed shipments, ensuring potential delivery risks are identified early and addressed proactively.

## Key Findings

The most influential factors affecting shipment delays include:

* Discount Offered
* Shipment Weight
* Prior Purchases
* Product Cost
* Customer Care Calls

## Business Impact

* Improved shipment risk visibility.
* Reduced operational and revenue losses.
* Enhanced logistics planning and resource allocation.
* Supported data-driven supply chain decision-making.
* Increased customer satisfaction through better delivery management.

## Future Enhancements

* Real-time shipment delay prediction.
* Integration with logistics management platforms.
* Inclusion of external factors such as weather and traffic data.
* Deployment as a scalable web-based application.

## Repository Structure

```text
Shipment-Delay-Prediction/
├── Shipment_Delay_Prediction.ipynb
├── data.csv
├── Shipment Delay Prediction.docx
├── Feature Importance Analysis for Shipment Delay Prediction.docx
└── README.md
```

## Author

**Penithalaxmi Nallapu**
B.E. Artificial Intelligence and Machine Learning
Chaitanya Bharathi Institute of Technology (CBIT)

