# Predictive Logistics System for Risk Mitigation (Shipment Delay Prediction)

## Project Overview
This project uses Machine Learning to predict shipment delays and help logistics teams identify high-risk deliveries before they occur. The system enables proactive decision-making, improves delivery performance, and reduces operational risks within supply chain networks.

## Problem Statement
Delayed shipments can result in customer dissatisfaction, increased operational costs, and revenue loss. The objective of this project is to build a predictive model capable of identifying shipments that are likely to be delayed, allowing businesses to take preventive actions.

## Objectives
- Predict shipment delays using historical logistics data.
- Identify key factors contributing to delivery delays.
- Improve supply chain efficiency through data-driven insights.
- Reduce business risks associated with late deliveries.

## Dataset Features
The dataset contains shipment-related information including:
- Warehouse details
- Product cost
- Shipment weight
- Customer purchase history
- Customer care calls
- Discount offered
- Delivery status

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- SMOTE
- GridSearchCV
- Matplotlib
- Seaborn
- Jupyter Notebook

## Methodology
1. Data Cleaning and Preprocessing
2. Missing Value Handling
3. Feature Engineering
4. Class Imbalance Handling using SMOTE
5. Model Training using XGBoost
6. Hyperparameter Tuning with GridSearchCV
7. Feature Importance Analysis
8. Model Evaluation

## Model Performance
### Final Model: XGBoost

| Metric | Value |
|----------|----------|
| Accuracy | 67.59% |
| Recall (Delayed Shipments) | 98% |
| Recall (On-Time Shipments) | 47% |

The model prioritizes identifying delayed shipments, ensuring that potential delivery risks are detected early.

## Key Findings
Feature importance analysis revealed that the following factors significantly influence shipment delays:

- Discount Offered
- Shipment Weight
- Prior Purchases
- Product Cost
- Customer Care Calls

## Business Impact
- Enables proactive shipment monitoring.
- Reduces operational and revenue losses.
- Improves logistics planning and resource allocation.
- Supports data-driven supply chain decision-making.
- Enhances customer satisfaction through better delivery management.

## Future Enhancements
- Real-time shipment delay prediction.
- Integration with logistics management systems.
- Inclusion of weather and traffic data.
- Deployment as a web application for operational use.

## Repository Structure

```
Shipment-Delay-Prediction/
│
├── Shipment_Delay_Prediction.ipynb
├── data.csv
├── Shipment Delay Prediction.docx
├── Feature Importance Analysis for Shipment Delay Prediction.docx
└── README.md
```

## Author

Penithalaxmi Nallapu
Bachelor of Engineering in Artificial Intelligence and Machine Learning
Chaitanya Bharathi Institute of Technology (CBIT)
