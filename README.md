# Lumpy Skin Disease Data Analysis

This repository contains an exploratory data analysis (EDA) of Lumpy Skin Disease (LSD) using a publicly available dataset. The goal is to extract insights and visualize trends that may aid in understanding the spread and characteristics of the disease.



## 📊 Dataset

The dataset provides case-level records of Lumpy Skin Disease outbreaks. It includes:
- `serotype`, `speciesDescription`, `epidemiologicalUnit`
- `numberAffected`, `numberSusceptible`
- `controlMeasures`, and others

Some irrelevant fields like `region`, `country`, and `reportingDate` were dropped during preprocessing.

---

## 📈 Exploratory Data Analysis

Performed using `pandas`, `seaborn`, and `matplotlib`, the EDA section includes:
- Summary statistics
- Null value handling
- Visual analysis of affected vs. susceptible counts
- Correlation matrix and distribution plots

---

## 🤖 Machine Learning Models

Several models were built to predict the presence of LSD (`lumpy` column as target):

### 1. Logistic Regression
- Standardized input features
- Evaluated using accuracy, precision, recall, and F1-score
- Confusion matrix and classification report

### 2. K-Nearest Neighbors (KNN)
- Euclidean distance metric
- ROC curve and AUC score for performance visualization

Future models can include:
- Random Forest
- XGBoost
- SVM

### 📊 Evaluation Metrics
- **Accuracy**
- **Confusion Matrix**
- **Classification Report**
- **ROC-AUC Curve**


