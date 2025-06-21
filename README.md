# Credit Risk Prediction

## Overview
This project aims to predict the credit risk of loan applicants using machine learning techniques. By analyzing key features of applicants, the model classifies them into risk categories, helping financial institutions make informed lending decisions. The notebook includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Project Workflow](#project-workflow)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Features
- **Data Exploration:** Analyze distributions, correlations, and feature importance.
- **Feature Engineering:** Create derived features and remove irrelevant variables.
- **Model Training:** Train multiple machine learning models, including ensemble methods.
- **Evaluation:** Assess model performance using metrics like accuracy, precision, recall, and specificity.
- **Hyperparameter Tuning:** Optimize models using Bayesian Optimization.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/atharv-asr-group/Credit-Risk-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Credit-Risk-Prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook credit-risk-prediction-training-and-eda.ipynb
   ```
2. Follow the steps in the notebook to preprocess data, perform EDA, engineer features, train models, and evaluate results.

## Project Workflow
### 1. Data Preprocessing
- Handle missing values.
- Encode categorical variables.
- Scale numerical features.

### 2. Exploratory Data Analysis (EDA)
- Visualize distributions and correlations.
- Analyze feature importance.

### 3. Feature Engineering
- Create derived features such as:
  - `loan_to_income_ratio`
  - `loan_to_emp_length_ratio`
  - `int_rate_to_loan_amt_ratio`
- Group features into categories like age groups, income groups, and loan amount groups.

### 4. Model Training
- Train multiple machine learning models, including:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - XGBoost
  - LightGBM
  - CatBoost
- Use ensemble methods like Voting Classifier for improved performance.

### 5. Hyperparameter Tuning
- Optimize model parameters using Bayesian Optimization.

### 6. Performance Evaluation
- Evaluate models using metrics:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **Specificity**
- Use confusion matrices to analyze predictions.

### 7. Final Model
- Train an ensemble model combining KNN, CatBoost, and LightGBM for final predictions.

## Results
The ensemble model achieved the following metrics:
- **Accuracy:** 94.4%
- **Precision:** High precision ensures minimal false positives.
- **Recall:** High recall ensures most defaults are detected.
- **Specificity:** High specificity avoids misclassifying reliable borrowers.

## Contributing
Contributions are welcome! If you'd like to contribute, please:
1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request with a detailed description of your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
