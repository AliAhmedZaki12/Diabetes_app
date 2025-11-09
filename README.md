# 🩺 Diabetes Risk Prediction Model 
# App : (https://diabetesapp-24aa.streamlit.app/)

A **Complete Machine Learning Pipeline** for Predicting Diabetes Risk

---

##  (Overview)

This project implements a **fully automated machine learning pipeline** to predict the likelihood of diabetes using structured health-related data.  
It covers everything from **data preprocessing** and **class balancing** to **hyperparameter tuning**, **evaluation**, and **model saving** — all organized into a clean, modular structure.

The core goal is to create a model that’s not only **accurate**, but also **robust**, **interpretable**, and **ready for production deployment**.

---
##  (Project Description)

The **Diabetes Risk Prediction Model** is a research-grade, end-to-end **machine learning system** designed to predict the likelihood of diabetes using structured health data.  
It automates the entire workflow — from **data cleaning** and **balancing** to **model training**, **tuning**, and **evaluation** — producing a robust, interpretable, and production-ready predictive model.

Unlike typical notebooks or one-pass scripts, this project follows a **modular and reusable design** with:
- Full preprocessing pipeline (scaling, encoding, imputing)
- Class balancing using **SMOTE**
- Two-stage optimization (Randomized + Grid Search)
- Clear visualization and reporting tools
- Model persistence for future deployment

---


## (Key Features)

### 🔹 1. Smart Data Handling
- Automatically identifies **numerical and categorical columns**.  
- Cleans, scales, and encodes data using `StandardScaler` and `OneHotEncoder`.  
- Ensures consistent preprocessing during both **training** and **inference**.

### 🔹 2. Handling Class Imbalance
- Uses **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset.  
- Reduces model bias and improves prediction quality for minority classes.

### 🔹 3. Advanced Model Optimization
- Core model: **RandomForestClassifier** (chosen for interpretability and stability).  
- Employs a two-stage optimization strategy:
  - `RandomizedSearchCV` — broad exploration of parameter space.  
  - `GridSearchCV` — fine-tuning for maximum performance.

### 🔹 4. Detailed Evaluation
- Evaluates the model with **Accuracy**, **Precision**, **Recall**, **F1-Score**, and **ROC-AUC**.  
- Generates a full **classification report** for detailed class-level metrics.  
- Visualizes performance through **Confusion Matrix** and **ROC Curve**.

### 🔹 5. Model Persistence
- Saves the trained model with `joblib` for future reuse or deployment.

---

