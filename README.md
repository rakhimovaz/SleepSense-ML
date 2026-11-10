# SleepSense: Machine Learning-Based Sleep Outcome Prediction

**Status:** Work in Progress | Academic Research Project

## Overview

SleepSense is a machine learning research project that aims to predict a later self-reported sleep outcome using baseline lifestyle and health data.

The project investigates how different machine learning algorithms perform on an imbalanced health dataset and which features contribute most to their predictions.

## Dataset

The study uses a publicly archived health dataset from Fukushima Prefecture, Japan, containing:

- **49,483 records** and **61 original variables**
- Health checkup data from 2014 and 2015
- **13 selected baseline features**, including age, BMI, blood pressure, smoking, and physical activity
- A binary sleep-related outcome recorded in 2015

**Source:** [Dryad Dataset](https://doi.org/10.5061/dryad.31zcrjdjn)

## Planned Machine Learning Models

- Logistic Regression
- Random Forest
- XGBoost

## Methodology

1. Exploratory Data Analysis (EDA)
2. Data preprocessing and feature selection
3. Stratified train-test split
4. Model training and hyperparameter tuning
5. Model evaluation using Precision, Recall, F1-score, ROC-AUC, and PR-AUC
6. Model explainability using SHAP
7. Interactive research dashboard development

## Current Progress

- [x] Initial dataset exploration
- [x] Selection of 13 baseline features
- [x] Stratified 80/20 train-test split
- [ ] Data preprocessing pipeline
- [ ] Model training and evaluation
- [ ] SHAP explainability
- [ ] Interactive dashboard
- [ ] Final research report

## Technologies

Python · Pandas · NumPy · Scikit-learn · XGBoost · SHAP · Matplotlib · Streamlit (planned)

## Research Team

- **Zuhra Rahimova**
- **Fotima Rahimova**
- **Aziza Hamidova**

Central Asian University — School of Engineering

## Disclaimer

This project is intended for academic research and demonstration purposes only. It is not a medical diagnostic tool.

Model results will be added after experiments are completed.
