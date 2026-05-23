# Molecular Property Prediction using Machine Learning

## Overview
This project is a Machine Learning-based molecular analysis system developed using Python to predict important chemical properties and classify drug-likeness from molecular structures.

## Features
- Predicts **Boiling Point**
- Predicts **Density**
- Predicts **Molecular Weight**
- Classifies **Drug vs Non-Drug molecules**
- Provides **3D molecular visualization**

## Tech Stack
- Python
- Jupyter Notebook
- RDKit
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- py3Dmol

## Machine Learning Models
- Random Forest Regressor (for property prediction)
- Random Forest Classifier (for drug classification)

## Workflow
1. Load molecular dataset (100 molecules)
2. Extract molecular descriptors using RDKit
3. Perform data preprocessing and feature engineering
4. Train ML models
5. Evaluate model performance
6. Visualize predictions and molecular structures

Note: Interactive py3Dmol visualizations may not render in GitHub preview; please run the notebook locally to view full 3D models.
