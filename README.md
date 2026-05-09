# College Clustering Analysis using K-Means

## Overview
This project applies Unsupervised Machine Learning techniques to cluster colleges and universities based on academic, financial, and demographic features.

The main objective was to discover hidden patterns and group similar institutions using the K-Means clustering algorithm.

The project includes:
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature scaling
- K-Means clustering
- Cluster evaluation
- PCA visualization

---

# Dataset Description

The dataset contains information about **777 universities and colleges** with **19 features** describing academic, financial, and demographic characteristics.

## Features Include
- Applications received
- Acceptance rate
- Enrollment numbers
- Tuition costs
- Room and board expenses
- Graduation rates
- Student-to-faculty ratio
- Percentage of alumni donations
- Expenditure per student
- Private/Public university label

---

# Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Checked for missing values and duplicates
- Handled outliers in selected numerical features
- Applied feature scaling using `StandardScaler`
- Encoded categorical variables
- Prepared data for clustering analysis

---

# Exploratory Data Analysis (EDA)

Performed extensive EDA to understand:
- Feature distributions
- Correlations between variables
- Tuition and expenditure patterns
- Differences between private and public institutions

Visualizations included:
- Histograms
- Boxplots
- Correlation heatmaps
- Scatter plots

---

# Clustering Model

## Algorithm
K-Means Clustering

## Why K-Means?
K-Means was selected because:
- It is efficient for grouping unlabeled data
- Works well with scaled numerical features
- Suitable for discovering hidden patterns in institutional data

---

# Cluster Evaluation

The clustering performance was evaluated using:

- Silhouette Score
- Elbow Method
- PCA visualization

The silhouette score helped measure how well-separated the clusters were.

---

# PCA Visualization

Principal Component Analysis (PCA) was applied to:
- Reduce dimensionality
- Visualize clusters in 2D space
- Compare cluster separation visually

---

# Key Contributions

- Performed full exploratory data analysis and preprocessing workflow.
- Applied scaling and feature transformation techniques for clustering.
- Built and evaluated K-Means clustering models.
- Used silhouette score and elbow method for cluster evaluation.
- Visualized clusters using PCA projections.
- Compared clustering patterns between private and public universities.
- Analyzed academic and financial patterns across institutions.

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
College-Clustering-Analysis-using-KMeans/
│
├── data/
├── notebooks/
├── images/
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

Add your repository link here:
```bash
https://github.com/ALAAMEKAWY56/College-Clustering-Analysis-using-K-Means
```

---

# 👩‍💻 Author

## Alaa Mekawi
AI & Machine Learning Engineer
