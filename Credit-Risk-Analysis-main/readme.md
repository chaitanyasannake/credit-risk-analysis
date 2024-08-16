# Credit Risk Modeling Project

## Overview

This project involves developing and optimizing credit risk prediction models using machine learning techniques. The goal is to improve the accuracy and reliability of predicting credit risk to help financial institutions make informed lending decisions. The project utilizes XGBoost and Random Forest models, applies dimensionality reduction and class balancing techniques, and evaluates model performance through various metrics.

## Table of Contents

1. [Project Description](#project-description)
2. [Data](#data)
3. [Methodology](#methodology)
4. [Model Development](#model-development)
5. [Performance Metrics](#performance-metrics)
6. [Results](#results)
7. [Installation and Setup](#installation-and-setup)
8. [Usage](#usage)
9. [Contributing](#contributing)

## Project Description

This project focuses on building predictive models for credit risk assessment using historical credit data. The objective is to predict the likelihood of default and enhance model accuracy through advanced techniques like grid search optimization, dimensionality reduction, and handling class imbalance.

## Data

- **Dataset:** Historical credit data from financial institutions.
- **Records:** 500,000+ samples.
- **Features:** Includes credit history, account information, and demographic details.
- **Target Variable:** Credit default (binary classification: default or no default).

## Methodology

1. **Data Preprocessing:**
   - **Data Cleaning:** Handling missing values, outliers, and inconsistencies.
   - **Feature Engineering:** Creating relevant features and encoding categorical variables.

2. **Dimensionality Reduction:**
   - **Principal Component Analysis (PCA):** Applied to reduce feature space and improve model performance.

3. **Class Balancing:**
   - **Synthetic Minority Over-sampling Technique (SMOTE):** Used to address class imbalance and improve model sensitivity to minority class.

4. **Model Development:**
   - **Models Used:** XGBoost and Random Forest.
   - **Hyperparameter Tuning:** Performed using grid search to optimize model performance.

## Model Development

1. **XGBoost Model:**
   - **Hyperparameters:** Optimized using grid search.
   - **Performance Metrics:** Improved performance by 12%, achieving a precision of 52% and recall of 70%.

2. **Random Forest Model:**
   - **Ensemble Learning:** Utilized to enhance predictive power and reduce overfitting.
   - **Performance Metrics:** Achieved 75% accuracy and reduced false negatives by 60%.

## Performance Metrics

- **Accuracy:** 75% (Random Forest)
- **Precision:** 52% (XGBoost, after optimization)
- **Recall:** 70% (XGBoost, after optimization)
- **False Negatives Reduction:** 60% (Random Forest)

## Results

- **XGBoost Performance Improvement:** Achieved a 12% increase in performance, with balanced precision and recall.
- **Random Forest Accuracy:** Reached 75% accuracy and significantly reduced false negatives.
- **Model Robustness:** Enhanced through PCA and SMOTE, processing over 500K records.

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/credit-risk-modeling.git
   cd credit-risk-modeling
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Setup Environment:**
   - Ensure Python 3.x is installed.
   - Install necessary libraries including `pandas`, `numpy`, `scikit-learn`, `xgboost`, and `imbalanced-learn`.

## Usage

1. **Run Data Preprocessing:**
   ```bash
   python preprocess_data.py
   ```

2. **Train Models:**
   ```bash
   python train_models.py
   ```

3. **Evaluate Models:**
   ```bash
   python evaluate_models.py
   ```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Submit a pull request.

## Author
- **Chaitanya Sannake** - [LinkedIn](https://www.linkedin.com/in/chaitanya-sannake-a73692226/)
