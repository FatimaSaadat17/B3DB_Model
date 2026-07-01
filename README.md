# B3DB_Model

A machine learning pipeline for molecular property modeling using structural fingerprints and dimensionality reduction techniques.

## Overview
This project explores molecular data using cheminformatics features and classical machine learning models. It focuses on transforming high-dimensional molecular representations into meaningful embeddings and building predictive models.

## Pipeline

The workflow includes:

- Data preprocessing of molecular datasets
- Generation of molecular fingerprints (Morgan fingerprints)
- Dimensionality reduction using:
  - PCA (Principal Component Analysis)
  - Truncated SVD
- Model training using Support Vector Machines (SVM)
- Hyperparameter optimization using RandomizedSearchCV

## Models Used
- Support Vector Machine (SVM)

## Feature Engineering
- Morgan fingerprints for molecular structure representation
- PCA for variance-based projection
- Truncated SVD for sparse high-dimensional reduction

## Model Tuning
- RandomizedSearchCV for hyperparameter optimization
- Cross-validation for robust evaluation

## Goal
To explore how molecular structural representations can be transformed and used to predict properties using classical machine learning models.

## Author
Fatima Saadat (@FatimaSaadat17)

## Tech Stack
- Python
- scikit-learn
- RDKit (if used)
- NumPy / Pandas
- Matplotlib (if used)

## Key Ideas
- High-dimensional molecular data can be compressed without major loss of information
- Fingerprints + dimensionality reduction improve model performance
- SVM performs well on structured chemical feature spaces

---# B3DB_Model
