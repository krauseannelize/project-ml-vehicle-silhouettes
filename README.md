# Vehicle Silhouettes Machine Learning

This project applies both supervised and unsupervised machine learning methods to the Vehicle Silhouettes dataset. The goal is to differentiate vehicles (bus, van, car) based on geometric features extracted from their silhouettes.

## Tools & Skills Used

![Data%20Science](https://img.shields.io/badge/Data%20Science-Machine%20Learning-%23DC143C)
![Python](https://img.shields.io/badge/Python-pandas-%233776AB)
![Python](https://img.shields.io/badge/Python-numpy-%233776AB)
![Python](https://img.shields.io/badge/Python-sklearn-%233776AB)
![Python](https://img.shields.io/badge/Python-seaborn-%233776AB)
![Python](https://img.shields.io/badge/Python-matplotlib-%233776AB)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-Interactive%20Analysis-%23C35817)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Cloud%20Analysis-%23F9AB00)

## Quick Access

- [Supervised | Jupyter Notebook](vehicle_ml_supervised.ipynb)
- [Supervised | Colab Notebook](https://colab.research.google.com/drive/1gexX8g6enIzGFFajfOlsLqbIJ_NlKhCu?usp=sharing)
- [Unsupervised | Jupyter Notebook](vehicle_ml_unsupervised.ipynb)
- [Unsupervised | Colab Notebook](https://colab.research.google.com/drive/1emJ5mp2ws0kyQn_qNT3slZE-bEK3Y4Nh?usp=sharing)
- [Project Description](project-description.md)
- [Vehicle Silhouettes Dataset](vehicle-silhouettes.csv)
- [Cleaned Dataset](vehicle-silhouettes-clean.csv)

## Project Overview

**Prospect Auto**, a chain of car repair shops, requested models to classify vehicles based on silhouette features. This repo demonstrates two approaches:

- **Supervised classification** → Predicting vehicle classes using labeled data.
- **Unsupervised clustering** → Grouping vehicles without labels to discover natural structure.

## Objectives

- Explore the Vehicle Silhouettes dataset.
- Build supervised models to classify vehicles.
- Apply unsupervised clustering methods to group vehicles.
- Compare results and assess which approach is most effective.

## Methodology

1. **Data Preparation**

   - Load and clean dataset.
   - Normalize and standardize features.
   - Split into training/testing subsets.

2. **Supervised Learning**

   - Train classification models.
   - Evaluate with accuracy, precision, recall, F1‑score.

3. **Unsupervised Learning**

   - Apply PCA for dimensionality reduction.
   - Train clustering models (e.g., k‑means).
   - Evaluate with silhouette score and inertia.

## Key Findings

- All supervised algorithms performed consistently well across classes, confirming strong generalization without significant overfitting.
- Logistic Regression emerged as the most balanced and reliable supervised model, achieving 95.1% accuracy on training data and 93.9% on test data.
- Unsupervised clustering (K-Means, Hierarchical, DBSCAN) revealed one dominant group with smaller overlapping sub-clusters that were imbalanced and did not align with true vehicle classes.
- While clustering is not a viable alternative for Prospect Auto’s classification needs, it may still provide value for exploratory analysis or anomaly detection.

## Assessment

| Approach | Grade | Instructor Feedback |
| --- | --- | --- |
| **Supervised Learning** | 100%  | “Really good documentation, all the main insights were present and the viz on point!”|
| **Unsupervised Learning** | 100% | “Great work! All comments were properly made and the insights/information achieved the requirements.” |
