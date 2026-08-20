# Credit Card Fraud Detection — EDA & Feature Engineering

## Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) and feature engineering workflow for a highly imbalanced credit card transaction dataset.

The goal of the project is to understand the underlying transaction patterns, investigate fraudulent behavior, assess data quality, identify meaningful relationships between variables, and engineer additional features that can support future machine learning workflows.

The project focuses on the complete data analysis process, from data inspection and cleaning to statistical analysis, visualization, class imbalance investigation, and feature engineering.

## Dataset

The project is based on a credit card transaction dataset containing anonymized transaction features and a binary target variable indicating whether a transaction is fraudulent.

The raw and processed CSV datasets are intentionally excluded from this repository because of their large file sizes.

The repository contains the analysis notebook and the generated HTML report, which document the complete analytical workflow.

## Project Objectives

The main objectives of this project are to:

- Understand the structure and characteristics of the dataset.
- Assess data quality and identify potential data issues.
- Perform data cleaning and preprocessing.
- Analyze the distribution of fraudulent and legitimate transactions.
- Explore relationships between transaction features and fraud occurrence.
- Investigate transaction amount and time-related patterns.
- Analyze the highly imbalanced target variable.
- Identify potentially informative features and relationships.
- Engineer additional features for downstream machine learning applications.
- Document the complete EDA workflow in a reproducible notebook.
- Generate an HTML report containing the analysis results.

## Project Workflow

The analysis follows a structured data science workflow:

1. Data Loading
2. Initial Data Inspection
3. Data Quality Assessment
4. Data Cleaning
5. Statistical Analysis
6. Univariate Analysis
7. Bivariate and Multivariate Analysis
8. Fraud vs. Legitimate Transaction Analysis
9. Class Imbalance Investigation
10. Feature Engineering
11. Feature Distribution and Relationship Analysis
12. Final Data Validation
13. EDA Report Generation

## Exploratory Data Analysis

The EDA process investigates several aspects of the dataset, including:

### Data Structure

- Dataset dimensions
- Data types
- Feature distributions
- Target variable distribution
- Summary statistics

### Data Quality

The project evaluates:

- Missing values
- Duplicate records
- Data types
- Potential inconsistencies
- Feature distributions
- Data integrity after preprocessing

### Fraud Analysis

Special attention is given to the difference between fraudulent and legitimate transactions.

The analysis investigates:

- Class distribution
- Transaction amount patterns
- Time-related behavior
- Feature distributions
- Relationships between anonymized features and the fraud target

Because fraudulent transactions represent a small minority of the dataset, class imbalance is treated as an important analytical consideration.

## Feature Engineering

Additional features are engineered from the available transaction information to provide more meaningful representations of the underlying data.

The feature engineering process includes transformations related to:

- Transaction time
- Transaction amount
- Feature aggregation
- Risk-oriented representations
- Numerical transformations

The engineered dataset is intended to provide a stronger foundation for future machine learning experiments.

## Key Analytical Areas

The project focuses on identifying patterns that can help answer questions such as:

- How imbalanced is the fraud classification problem?
- How do fraudulent transactions differ from legitimate transactions?
- What transaction characteristics are associated with fraudulent activity?
- How does transaction amount vary between classes?
- Are there meaningful time-related patterns?
- Which anonymized features show stronger relationships with the target?
- Which engineered features may be useful for future predictive modeling?

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Jupyter Notebook

## Project Files

### `creditcard.ipynb`

The main Jupyter Notebook containing the complete data analysis and feature engineering workflow.

### `creditcard_EDA_report.html`

An exported HTML version of the analysis report for easier viewing without opening the notebook.

### Dataset Files

The raw and processed CSV files are not stored in the GitHub repository because of their large size.

The local analysis uses:

- `creditcard.csv`
- `cleaned_creditcard_data.csv`

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Eng-Abdullah-H/credit-card-fraud-eda.git
```

### 2. Navigate to the project directory

```bash
cd credit-card-fraud-eda
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

On Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### 5. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
```

### 6. Open the notebook

```bash
jupyter notebook creditcard.ipynb
```

## Results

The project provides a complete EDA and feature engineering workflow for understanding credit card transaction fraud.

The analysis establishes the data quality, class imbalance, transaction behavior, feature relationships, and engineered representations required for a future machine learning fraud detection pipeline.

The generated HTML report provides a consolidated view of the exploratory analysis and visual findings.

## Future Work

Potential next steps for this project include:

- Building baseline fraud classification models.
- Applying appropriate techniques for handling class imbalance.
- Performing feature selection.
- Comparing multiple machine learning algorithms.
- Hyperparameter tuning.
- Evaluating models using fraud-focused metrics such as Precision, Recall, F1-score, PR-AUC, and ROC-AUC.
- Performing cross-validation.
- Developing an end-to-end fraud detection pipeline.
- Deploying the final model as an API or application.

## Author

**Abdullah Hegazy**

Data & AI / Machine Learning Enthusiast

GitHub: [Eng-Abdullah-H](https://github.com/Eng-Abdullah-H)
