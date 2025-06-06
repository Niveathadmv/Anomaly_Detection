# Anomaly Detection Using Isolation Forest and SHAP for Enhanced Interpretation

This project demonstrates how to detect anomalies in avocado sales data using the Isolation Forest algorithm, and how to interpret the model's predictions using SHAP (SHapley Additive exPlanations).

# Objective
To identify outliers in avocado sales data and understand the key features contributing to anomaly detection using a combination of machine learning and model interpretability techniques.

# Dataset Overview
We used the Avocado Sales Dataset, which includes:

Date, Year

AveragePrice

Total Volume

PLU codes: 4046, 4225, 4770

Total Bags

type: Conventional or Organic

# Key Steps
## Preprocessing:

Selected relevant features.

Standardized the dataset.

Split into training and test sets.

## Modeling with Isolation Forest:

Trained the model to flag data points as anomalies (-1) or normal (1).

Visualized anomalies via scatter plots.

## Model Interpretation with SHAP:

Applied SHAP values to interpret why certain points were flagged as anomalies.

Identified key features like 4770 and Total Bags as major drivers.

Context-sensitive features like Total Volume and AveragePrice were shown to vary in influence.

# Key Insights
Isolation Forest is effective for spotting irregularities based on path length in trees.

SHAP provides transparency into feature influence, helping stakeholders understand the “why” behind anomaly flags.

Helps differentiate between clear anomalies (e.g., extreme Total Bags) and complex, value-dependent ones (e.g., AveragePrice).

# Conclusion
Combining Isolation Forest with SHAP offers a powerful, interpretable approach to anomaly detection. It not only catches outliers but also explains them — critical for making data-driven business decisions.
