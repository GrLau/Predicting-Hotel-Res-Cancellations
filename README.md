# Predicting Hotel Reservation Cancellations
This repository contains Jupyter notebooks that apply machine learning techniques to predict hotel reservation cancellations. The dataset used is slightly imbalanced, so we employ various strategies to address this issue, including class weighting and resampling methods.

You can read the published article here: https://jhss.scholasticahq.com/article/133741-hotel-reservation-cancellations-predictive-modeling-and-feature-impact-analysis

## Features of the Project
- **Machine Learning Models**:
  - Logistic Regression
  - Random Forest
  - XGBoost
 
- **Handling Class Imbalance**:
  - Setting `class_weight = "balanced"` for models that support it
  - Applying SMOTE (Synthetic Minority Over-Sampling Technique) for data augmentation
 
- **Hyperparameter Tuning**:
  - GridSearchCV to optimize model parameters
 
- **Evaluation Metrics**:
  - F1-score
  - Precision
  - Recall
 
- **Interpretability & Feature Importance**:
  - SHAP (SHapley Additive exPlanations) analysis
  - Visualizing feature contributions through beeswarm plots and other interpretability techniques
 
### References:
Raza, Ahsan. “Hotel Reservations Dataset.” Www.kaggle.com, www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset.
