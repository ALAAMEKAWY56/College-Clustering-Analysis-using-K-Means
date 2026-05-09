# ❤️ Heart Disease Classification using SVM

## Overview
This project builds a Machine Learning model to predict heart disease using a Support Vector Machine (SVM) with an RBF kernel.

The main objective was to develop a clinically reliable classifier while minimizing False Negatives, since failing to detect heart disease cases can be dangerous in real-world healthcare applications.

The project includes:
- Data cleaning
- Feature preprocessing
- Pipeline construction
- Model training and evaluation
- Visualization and analysis

---

# Dataset Features

The dataset contains medical and clinical attributes including:

- Age
- Sex
- ChestPainType
- RestingBP
- Cholesterol
- FastingBS
- RestingECG
- MaxHR
- ExerciseAngina
- Oldpeak
- ST_Slope
- HeartDisease (Target)

---

# Data Cleaning

Medically invalid values were identified and handled:

- `RestingBP = 0`
- `Cholesterol = 0`
- `Oldpeak < 0`

These values were converted into `NaN` and handled using:
- **KNN Imputation (k=5)**

This improved data quality while preserving dataset integrity.

---

# Preprocessing Pipeline

A complete preprocessing workflow was implemented using:
- `Pipeline`
- `ColumnTransformer`

## Numerical Features
- KNNImputer
- StandardScaler

## Categorical Features
- OneHotEncoder for nominal features
- OrdinalEncoder for ordered features (`ST_Slope`)

The pipeline ensures:
- No data leakage
- Consistent preprocessing
- Proper feature transformation
- Compatibility with SVM models

---

# Model

## Algorithm
Support Vector Machine (SVM)

## Kernel
RBF (Radial Basis Function)

The dataset is non-linearly separable, making the RBF kernel a suitable choice for capturing complex decision boundaries.

---

# Key Contributions

- Performed data cleaning and handled medically invalid values using KNN Imputation.
- Built a complete preprocessing pipeline using `Pipeline` and `ColumnTransformer`.
- Applied feature scaling, encoding, and transformation techniques for numerical and categorical features.
- Developed and optimized an SVM classifier with RBF kernel for non-linear classification.
- Focused on minimizing False Negatives to improve clinical reliability of predictions.
- Evaluated model performance using Accuracy, Precision, Recall, and F1-Score metrics.
- Visualized dataset patterns and model insights using Matplotlib and Seaborn.

---

# Results (Test Set)

| Metric | Score |
|---|---|
| Accuracy | ~88% |
| Precision | ~86% |
| Recall | ~93% |
| F1 Score | ~89% |

The high recall score demonstrates strong capability in detecting heart disease cases while reducing missed diagnoses.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Project Structure

```bash
Heart-Disease-classification-using-SVM/
│
├── data/
├── notebooks/
├── images/
├── models/
├── README.md
└── requirements.txt
```

---

# Installation

```bash
pip install -r requirements.txt
```

---

# Run the Project

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

# GitHub Repository

GitHub Repo:  
https://github.com/ALAAMEKAWY56/Heart-Disease-classification-using-SVM

---

# 👩‍💻 Author

## Alaa Mekawi
AI & Machine Learning Engineer
