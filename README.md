# DEPI Graduation Project

## Project Overview
This project focuses on solving a classification problem using the IBM Telco Customer Churn dataset available on Kaggle. The main goal is to build and compare multiple machine learning models to accurately predict customer churn. The project follows a structured workflow from data collection to final evaluation.

## Project Workflow

### 1. Data Collection
- The IBM Telco Customer Churn dataset was downloaded from Kaggle.
- Initial inspection was done to ensure data quality and completeness.

### 2. Exploratory Data Analysis (EDA)
- Statistical summaries and visualizations helped understand feature distributions.
- Relationships between features and churn target variable were explored.
- Missing values and outliers were identified and addressed.

### 3. Data Preprocessing
- Data cleaning steps included encoding categorical variables and handling missing data.
- Feature scaling was applied where appropriate.
- Dataset was split into training and testing sets.

### 4. Modeling
- Several classification algorithms were trained and evaluated, including:
  - Random Forest
  - Gradient Boosting
  - Logistic Regression
- Baseline performances were established before tuning.

### 5. Hyperparameter Tuning
- Random Search and Grid Search methods were used to find optimal hyperparameters.
- Each model was fine-tuned accordingly.
- Cross-validation ensured model robustness.

### 6. Evaluation
- Performance was measured using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC AUC
- Confusion matrices and ROC curves were generated for visual analysis.

## Modeling Results

| Model              | Train Accuracy | Test Accuracy | Precision | Recall | F1-Score | ROC AUC |
|--------------------|----------------|---------------|-----------|--------|----------|---------|
| Random Forest      | 0.910          | 0.860         | 0.861     | 0.865  | 0.863    | 0.936   |
| Gradient Boosting  | 0.873          | 0.853         | 0.845     | 0.871  | 0.858    | 0.935   |
| Logistic Regression| 0.816          | 0.823         | 0.806     | 0.860  | 0.832    | 0.895   |

**Best Model:**  
Random Forest achieved the best performance overall, showing excellent predictive accuracy and generalization capability.

---

This README summarizes the key steps and results from the DEPI Graduate Project notebook using the IBM Telco Customer Churn dataset from Kaggle.
