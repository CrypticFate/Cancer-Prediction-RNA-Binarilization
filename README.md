# Explainable Machine Learning for Cancer Prediction via RNA Binarilization

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-20BEFF?logo=kaggle)](https://www.kaggle.com/datasets/tianjiechen/tcga-rna-datasets)

## Overview

This repository implements the methods from **"Explainable machine learning approach for cancer prediction through binarilization of RNA sequencing data"** ([PLOS ONE](https://doi.org/10.1371/journal.pone.0302947)). It demonstrates how binarilization of gene expression data enhances interpretability while maintaining high predictive accuracy for cancer classification.

## Key Features

- **RNA Binarilization**: Quantile-based discretization of continuous expression values into 10 interpretable bins
- **Chi-Square Feature Selection**: Univariate selection of top discriminative gene-bin combinations
- **Class Imbalance Handling**: SMOTE oversampling + class-weighted models for imbalanced cancer datasets
- **Five ML Models**: Decision Tree, Random Forest, XGBoost, SVM, Neural Network
- **Robust Evaluation**: GMean, MCC, F1-Score, and AUC metrics designed for imbalanced classification
- **Explainability**: SHAP analysis and feature importance for model interpretability
- **Stratified Cross-Validation**: Maintains class proportions across train/test splits

## Supported Datasets

- **Liver Cancer** RNA Data
- **Lung Cancer** RNA Data  
- **Prostate Cancer** RNA Data
- **Thyroid Cancer** RNA Data

(Available on [Kaggle](https://www.kaggle.com/datasets/tianjiechen/tcga-rna-datasets))
