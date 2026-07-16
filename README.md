# MLP Project – Binary Classification on Kaggle Competition

> **Author:** Vaishnavi Bhan  
> **Roll Number:** 22F3001086

## Project Overview

This project was developed as part of a Machine Learning Practice (MLP) assignment based on a Kaggle binary classification competition. The objective was to analyze the provided dataset, perform exploratory data analysis, preprocess the data, establish baseline models, engineer features, and develop a predictive machine learning model capable of accurately classifying the target variable.

The complete workflow follows a structured machine learning pipeline beginning with data exploration and ending with model evaluation and Kaggle submission.

---

## Objectives

- Perform comprehensive exploratory data analysis (EDA).
- Understand dataset characteristics and quality.
- Identify missing values and highly correlated features.
- Build baseline classification models.
- Apply preprocessing and feature engineering techniques.
- Train and evaluate machine learning models.
- Generate predictions for Kaggle submission.
- Achieve a competitive leaderboard ranking.

---

# Dataset

The project uses the datasets provided by the Kaggle competition:

- `train.csv`
- `test.csv`

The training dataset contains feature columns along with the target variable used for supervised learning, while the test dataset is used for generating final competition predictions.

---

# Project Workflow

## 1. Data Exploration

The first phase involved understanding the structure of the dataset.

Performed analyses included:

- Dataset shape
- Data types
- Missing value analysis
- Summary statistics
- Feature distributions
- Unique value counts
- Duplicate detection

A reusable dataset overview function was created to automate the exploratory process.

---

## 2. Exploratory Data Analysis (EDA)

Several exploratory techniques were applied to better understand the dataset.

These included:

- Missing value visualization
- Numerical feature statistics
- Correlation matrix generation
- Identification of highly correlated features
- High-cardinality categorical feature detection
- Feature summary generation

This stage helped identify important variables while highlighting data quality issues that required preprocessing.

---

## 3. Data Preprocessing

Multiple preprocessing strategies were explored.

### Missing Value Handling

Two different approaches were evaluated:

- Removing rows containing missing values
- Imputing missing values

Imputation strategy:

- Numerical features → Mean Imputation
- Categorical features → Most Frequent Value Imputation

---

### Feature Selection

Correlation analysis was performed to identify informative numerical features.

Highly relevant features were retained for model development in order to reduce unnecessary noise and improve learning efficiency.

---

## 4. Baseline Models

Before building predictive models, baseline performance was established using Scikit-learn's `DummyClassifier`.

Different baseline strategies were evaluated to understand the minimum expected performance.

This provides an important benchmark against which more sophisticated models can be compared.

---

## 5. Model Development

After preprocessing and feature selection, a Logistic Regression classifier was trained.

The workflow included:

- Train/Test split
- Model training
- Prediction generation
- Performance evaluation

Evaluation metrics included:

- Accuracy
- Classification Report
- Confusion Matrix

---

## Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub

---

# Machine Learning Pipeline

```
Raw Dataset
      │
      ▼
Data Exploration
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Missing Value Analysis
      │
      ▼
Data Cleaning
      │
      ▼
Feature Selection
      │
      ▼
Baseline Models
      │
      ▼
Logistic Regression
      │
      ▼
Prediction
      │
      ▼
Kaggle Submission
```

---

# Results

The project successfully implemented a complete end-to-end supervised machine learning workflow.

Key outcomes include:

- Comprehensive exploratory data analysis.
- Identification of missing values and correlated features.
- Comparison of multiple preprocessing strategies.
- Construction of baseline classification models.
- Development of a Logistic Regression classifier.
- Generation of valid Kaggle competition submissions.

Most notably, the final solution achieved a **Top 150 leaderboard ranking** among **more than 1,500 participants**, demonstrating the effectiveness of the implemented preprocessing and modeling pipeline.

---

# Skills Demonstrated

This project demonstrates practical experience in:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Missing Value Imputation
- Feature Engineering
- Correlation Analysis
- Feature Selection
- Baseline Model Evaluation
- Logistic Regression
- Classification Metrics
- Model Validation
- Machine Learning Workflow Design
- Kaggle Competition Participation

---

# Repository Structure

```
.
├── train.csv(or zip of train.csv)
├── test.csv
├── mlp_project.zip
├── 22f3001086_notebook_t12025.ipynb
├── kaggle.json
└── README.md
```

---

# Conclusion

This project showcases a structured machine learning workflow for solving a real-world binary classification problem. Beginning with exploratory analysis and progressing through preprocessing, feature selection, baseline evaluation, model development, and competition submission, the project emphasizes reproducible machine learning practices.

Achieving a **Top 150 position out of 1,500+ participants** on the Kaggle leaderboard highlights the competitiveness of the solution and demonstrates practical proficiency in data preprocessing, model development, and predictive analytics.

---

## Author

**Vaishnavi Bhan**  
**Roll Number:** 22F3001086
