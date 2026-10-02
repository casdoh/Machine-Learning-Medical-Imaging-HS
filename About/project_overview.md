# Machine Learning for Medical Imaging in Hidradenitis Suppurativa

## Overview

This MSc project investigated spatial immune dysregulation in hidradenitis suppurativa (HS) using fluorescence microscopy, quantitative image analysis and machine learning.

The project examined inflammasome, complement, metabolic and lymphocyte markers in HS tissue, exploring their expression, localisation and spatial relationships.

## Computational Approach

- Quantitative fluorescence image analysis
- Cell and marker quantification
- Colocalisation analysis
- Intensity distribution analysis
- Spatial analysis
- Machine learning classification
- Model evaluation and comparison

## Machine Learning

Four classification approaches were implemented in R:

- Support Vector Machine (SVM)
- k-Nearest Neighbours (kNN)
- Random Forest
- XGBoost

Models were repeatedly trained and evaluated using train/test splits and cross-validation. Performance was assessed using:

- Accuracy
- F1-score
- Cohen's Kappa
- ROC-AUC
- Sensitivity
- Specificity

## Tools & Technologies

**Languages:** R, Python

**Packages:** `caret`, `tidyverse`, `ggplot2`, `pROC`, `randomForest`, `xgboost`

**Image analysis:** Fiji/ImageJ, Cellpose

**Methods:** Fluorescence microscopy, quantitative image analysis, colocalisation analysis, intensity analysis, spatial analysis, machine learning, classification and cross-validation

## Code

The `Code/` folder contains selected scripts demonstrating the computational methods used throughout the project.

The repository contains code examples and methodological workflows only. Original datasets, patient-level data and unpublished research results are not included.
