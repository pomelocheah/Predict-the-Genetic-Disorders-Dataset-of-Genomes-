# Predicting Genetic Disorders Using Machine Learning

## Project Overview
This project focuses on predicting genetic disorders based on patient demographic, clinical, and genetic information.  
The objective is to apply a complete **data preprocessing pipeline** followed by **machine learning classification models** to analyse and predict genetic disorder outcomes.

This repository is developed as part of an academic assignment and demonstrates proper data cleaning, transformation, and reduction techniques.

---

## Dataset Description
The dataset contains patient-level medical and genetic information, including:

- Patient demographics (age, gender, family history)
- Genetic inheritance indicators
- Medical test results
- Clinical symptoms
- Target variables:
  - **Genetic Disorder**
  - **Disorder Subclass**

The dataset includes missing values, mixed data types, and categorical variables that require preprocessing before model training.

---

## Data Preprocessing (Part A)

### 1. Data Cleaning
The following data cleaning steps were applied:
- Identification of missing values using null value counts and percentages
- Removal of features with excessively high missing rates
- Median imputation for numerical features
- Mode (most frequent) imputation for categorical features
- Verification to ensure no remaining missing values in processed features

### 2. Data Transformation
Data transformation techniques include:
- Conversion of non-numeric values to numeric format where applicable
- Encoding of categorical variables (e.g. Yes/No, Gender)
- Feature scaling using standardization or normalization techniques

### 3. Data Reduction
To reduce dimensionality and noise:
- Feature selection based on relevance
- Optional application of dimensionality reduction techniques such as PCA

### Machine Learning Models (Part B)

### 1. Machine Learning Models apply
The following machine learning models will include 5 machine learning algo.
### 2. Compare the performance by using metricss
The metrics that will be use to compare the models is accurart,precission,recall, F1-score......

## Project Structure

```text
Predict-the-Genetic-Disorders-Dataset-of-Genomes-/
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── data/
|   |─ test_genetic_disorders.csv
│   └── train_genetic_disorders.csv
│
├── README.md
├── requirements.txt
└── .gitignore
