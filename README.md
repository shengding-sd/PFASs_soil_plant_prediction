# PFASs_soil_plant_prediction
A Transferable Machine Learning Framework for Predicting PFAS Bioaccumulation in Crops Across Diverse Environments
# Overview
Predict plant bioaccumulation of PFAS; Integrate PFAS molecular characteristics, plant traits, and soil/environmental factors; Support screening of emerging PFAS with limited experimental data
# Dataset
train set.xlsx is the training set; test set.xlsx is the test set; Reference.xlsx is the source reference set; all data.xlsx is for LOSO; maize set and wheat set are for field validation and few-shot local calibration.
# Machine Learning
Ridge; MLP; RandomForest; Catboost; Bayesian-optimized CatBoost
# Model Interpretation
SHAP-based feature importance; Molecular descriptor analysis; Soil and environmental factor effects; Nonlinear relationships and threshold effects
# Validation
Group-based cross-validation; Leave-One-PFAS-Out (LOPFASO); Leave-One-Species-Out (LOSpeciesO); Leave-One-Study-Out (LOSO); External validation
# Spatial Prediction
National-scale prediction of PFAS accumulation in crops; Environmental domain delineation; Identification of high-accumulation regions; Risk-oriented agricultural mapping
# Local Calibration
Environmental clustering; Active sampling strategy; Few-shot local calibration; Adaptation of the global model to local conditions
# Python packages
python=3.10.10
