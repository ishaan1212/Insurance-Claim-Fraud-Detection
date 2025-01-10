# Insurance-Claim-Fraud-Detection

## Overview
This project focuses on detecting fraudulent insurance claims using advanced machine learning techniques. It involves comprehensive data preprocessing, exploratory data analysis (EDA), model building, evaluation, and interpretation. The project also outlines plans for further enhancements, such as deploying the model via APIs and creating an interactive dashboard for visualization.

---

## Project Workflow

### 1. Data Preprocessing
- Handled missing values, outliers, and performed label encoding for categorical variables.
- Scaled numerical features to improve model efficiency.

### 2. Exploratory Data Analysis (EDA)
- Conducted an in-depth analysis to understand key factors affecting fraud.
- Visualized relationships between variables to identify trends and patterns.

### 3. Model Building
- Implemented and evaluated multiple machine learning models:
  - **Logistic Regression**
  - **Random Forest**
  - **XGBoost**
  - **LightGBM (Final Model)**

### 4. Model Optimization
- Used **Grid Search** for hyperparameter tuning.
- Applied **SMOTE (Synthetic Minority Oversampling Technique)** to handle data imbalance.

### 5. Model Evaluation
- Evaluated models based on precision, recall, F1-score, and accuracy.
- Achieved an accuracy of **81%** with LightGBM and a significant improvement in fraud detection (recall for fraud: **64%**).

### 6. Explainability
- Utilized **SHAP (SHapley Additive exPlanations)** to interpret model predictions and identify key features contributing to fraud detection.
  - **Top Feature**: `Incident Severity` was identified as the most significant factor.

---

## Future Enhancements
- **Interactive Dashboard**:
  - Build an interactive dashboard using **Power BI** to visualize fraud trends, predictions, and key metrics.
- **API Deployment**:
  - Deploy the LightGBM model via an API to provide real-time fraud prediction services.
- **Additional Model Fine-Tuning**:
  - Further improve the model using advanced techniques like feature engineering and ensemble learning.

---

## Technologies Used
- **Programming Languages**: Python
- **Libraries**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost, LightGBM, SHAP
- **Tools**: Jupyter Notebook, Power BI
- **Techniques**: SMOTE, Hyperparameter Tuning, Grid Search

---

## Setup Instructions

### Prerequisites
1. Python 3.x installed on your machine.
2. Required Python libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn xgboost lightgbm shap
3. Jupytr Notebook or any IDE for running the python code

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/ishaan1212/Insurance-Claim-Fraud-Detection.git
2. Navigate to the project directory
   ```bash
   cd Insurance-Claim-Fraud-Detection
3. Open the Jupyter Notebook and run the code cells in order to execute the project.


