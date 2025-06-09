# AWS Machine Learning Nanodegree - Bike Sharing Demand Prediction Project

## Overview

This repository contains the project files submitted for the **AWS Machine Learning Nanodegree Program**. The project focuses on predicting bike sharing demand using machine learning techniques with AutoGluon and AWS services.

## Project Description

The goal of this project is to build and optimize machine learning models to predict bike sharing demand based on historical usage patterns and weather data. The project demonstrates:

- Exploratory Data Analysis (EDA)
- Feature Engineering 
- Model Training with AutoGluon
- Hyperparameter Optimization
- Model Performance Evaluation
- Kaggle Competition Submission

## 📁 Repository Structure

```
├── README.md                          # This file
├── submissions/                       # Main project deliverables
│   ├── project_report.html           # Comprehensive project report
│   ├── bike_sharing_notebook.ipynb   # Complete Jupyter notebook
│   └── model_train_score.png
|   └── model_test_score.png          # Model outputs and visualizations
├── various files (test, train, submissions) # Dataset files
```

## 🚀 Getting Started

**For project reviewers, please navigate to the [`Submissions/`](./Submissions/) folder to access all required project deliverables.**

The main submission files include:
- **Project Report**: Analysis and findings
- **Jupyter Notebook**: Complete code implementation

## Key Results

### Model Performance Progression
- **Initial Model**: RMSE = 1.799 (Kaggle Score)
- **With Feature Engineering**: RMSE = 0.643 (64% improvement)
- **With Hyperparameter Optimization**: RMSE = 0.525 (71% total improvement)

### Key Features Added
- **Hour extraction** from datetime (captured commuting patterns)
- **Categorical encoding** of weather and seasonal variables
- **Advanced hyperparameter tuning** with AutoGluon

## Technologies Used

- **AutoGluon**: Automated machine learning framework
- **Python**: Data analysis and modeling
- **Pandas/NumPy**: Data manipulation
- **Matplotlib/Seaborn**: Data visualization
- **Kaggle**: Competition platform for model evaluation

## Project Highlights

✅ **Exploratory Data Analysis**: Comprehensive analysis revealing temporal and weather-based usage patterns

✅ **Feature Engineering**: Strategic feature creation that improved model performance by 64%

✅ **Model Optimization**: Hyperparameter tuning achieving additional 18% improvement

✅ **Ensemble Learning**: Leveraged AutoGluon's stacking capabilities for optimal performance

✅ **Real-world Application**: Submitted to Kaggle competition with significant performance gains

## AWS ML Nanodegree Program

This project was completed as part of the **AWS Machine Learning Nanodegree Program**, demonstrating practical application of:
- AWS cloud services for ML workflows
- AutoML techniques for rapid prototyping
- Feature engineering best practices
- Model evaluation and optimization strategies

---

**📋 For detailed project submission materials, please visit the [`submissions/`](./submissions/) directory.**

*Project completed as part of the AWS Machine Learning Nanodegree Program - Udacity*
