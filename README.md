# HCV Multi-Method XAI Pipeline

This repository contains the full experimental code for the paper:

**"Cross-Model Explainability Consistency in Hepatitis C Stage Classification:
A SHAP, LIME, and Counterfactual Analysis Across Five Machine Learning Architectures"**

Khalid Alalawi, College of Computer Science and Engineering, Taibah University

## Contents
- `HCV_MultiXAI_Pipeline.ipynb` — Google Colab notebook containing:
  - Leakage-free preprocessing pipeline
  - Five model training scripts (LR, RF, XGBoost, LightGBM, SVM)
  - SHAP global and stage-specific explainability analyses
  - LIME local explainability analyses
  - DiCE counterfactual generation
  - Cross-model Spearman agreement analysis

## Dataset
The UCI HCV dataset is publicly available at:
https://doi.org/10.24432/C5D612

## Requirements
Run in Google Colab. All dependencies are installed within the notebook.

## License
MIT License
