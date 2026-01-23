# Walmart Sales Forecasting – Notebook

## Overview
This notebook implements an **end-to-end machine learning workflow** for the Walmart sales dataset.  
It is designed for **experimentation, understanding, and prototyping** before converting the logic into modular scripts and an Airflow pipeline.

## Workflow Covered
- Data loading and merging (`train`, `test`, `features`, `stores`)
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Train / validation split
- Model training
- Model evaluation and insights


## Tech Stack
- Python
- pandas, NumPy
- matplotlib / seaborn
- scikit-learn 
- Colab

## Purpose of This Notebook
- Rapid experimentation
- Feature engineering exploration
- Model prototyping
- Experimentation before using mlflow and airflow

## From Notebook to Pipeline
This notebook serves as the **prototype** for the production ML pipeline:
- Preprocessing → `src/preprocess.py`
- Training → `src/train_model.py`
- Orchestration → Airflow DAG



## Notes
Focus is on **clarity, correctness, and learning**, not just model performance.  
The logic here is later modularized and automated using Airflow and MLflow.

