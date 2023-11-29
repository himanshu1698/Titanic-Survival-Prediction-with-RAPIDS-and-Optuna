# Titanic Survival Prediction with RAPIDS and Optuna
 


## Overview

This project demonstrates how to leverage the power of RAPIDS (cuml) for GPU-accelerated machine learning and Optuna for efficient hyperparameter tuning. The goal is to predict the survival of passengers on the Titanic using the famous Kaggle dataset.


## Requirements

- Python 3.x
- RAPIDS cuML library
- Optuna
- Other dependencies (specified in `requirements.txt`)

## RAPIDS (cuML)
RAPIDS is an open-source data analytics and machine learning acceleration platform. It allows you to perform end-to-end data science and analytics pipelines entirely on GPUs. In this project, we utilize cuML, the machine learning library of RAPIDS, for training a Random Forest classifier on the GPU.


## Optuna
Optuna is an open-source hyperparameter optimization framework. It automates the process of finding the best hyperparameters for machine learning models efficiently. In this project, we use Optuna to search for the optimal hyperparameters of our Random Forest classifier.