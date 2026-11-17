# E-commerce Purchase Conversion Prediction

Predicting online purchase conversion using machine learning to support data-driven marketing decisions.

## Project Overview

This academic project develops an end-to-end predictive analytics workflow to estimate whether an e-commerce website session will result in a purchase.

The project uses 2,500 synthetic website sessions generated with AI assistance. The dataset does not contain real customer information.

## Business Objective

Estimate purchase probabilities to help marketing teams prioritize customer engagement actions and allocate resources more effectively.

## Methodology

1. Data integration from four simulated business tables.
2. Data quality checks and cleaning.
3. Exploratory Data Analysis (EDA).
4. Feature preparation and train-test splitting.
5. Training and evaluation of four classification models.
6. Purchase probability scoring and marketing prioritization.

## Model Performance

| Model | ROC AUC |
|---|---|
| Logistic Regression | 0.777 |
| Random Forest | 0.750 |
| Decision Tree | 0.708 |
| K-Nearest Neighbors | 0.664 |

Logistic Regression achieved the highest test ROC AUC and was selected for the final scoring demonstration.

## Business Application

Predicted purchase probabilities were grouped into three marketing priority categories:

- High priority: Probability >= 0.70
- Medium priority: 0.40 <= Probability < 0.70
- Low priority: Probability < 0.40

These thresholds are illustrative and would require further validation before use in a real marketing campaign.

## Tools and Technologies

- Python
- Pandas
- Scikit-learn
- Predictive Modeling
- Data Cleaning and Exploratory Analysis
- Classification Model Evaluation

## Limitations

- The dataset is synthetic and does not represent actual customer behavior.
- Model performance has not been validated on real-world e-commerce data.
- Data preprocessing and scoring procedures would require further validation before deployment.

## AI Usage

AI tools assisted throughout the development process, including coding, troubleshooting, and documentation. The workflow was developed step by step, with review and interpretation of each stage.

## Author

Juan Marcos Rodelgo Villanueva
Business Analytics Student — Universidad Autónoma de Madrid
