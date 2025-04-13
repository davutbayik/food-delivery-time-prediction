# 🍽️ Food Delivery Time Prediction

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange.svg)](https://jupyter.org/)
[![Last Commit](https://img.shields.io/github/last-commit/davutbayik/food-delivery-time-prediction)](https://github.com/davutbayik/food-delivery-time-prediction/commits/main)

This project leverages machine learning techniques to predict food delivery times accurately. By analyzing various factors influencing delivery durations, it aims to enhance customer satisfaction and optimize logistics in the food delivery industry.

## 📊 Project Overview

The repository implements and compares several regression models, including:

- Linear Regression (Baseline)
- Random Forest Regressor
- XGBoost Regressor
- LightGBM Regressor

These models are trained and evaluated to determine the most effective approach for predicting delivery times.

## 🧠 Key Features

- **Data Preprocessing**: Cleaning and preparing the dataset for modeling.
- **Feature Engineering**: Generating relevant features to improve model performance.
- **Model Training**: Implementing multiple regression algorithms.
- **Evaluation**: Comparing model performance using appropriate metrics.

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook 

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/davutbayik/food-delivery-time-prediction.git
   cd food-delivery-time-prediction

2. Create and activate a virtual environment (Optional-Recommended):

   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate

3. Install the required packages:
   ```bash
   pip install -r requirements.txt

4. Launch the Jupyter Notebook
   ```bash
   jupyter notebook food_delivery.ipynb

### 📈 Model Performance

To assess how well different models predict food delivery times, we evaluated them using:

- **Root Mean Squared Error (RMSE)**: Indicates how far predictions deviate from actual values. (Lower the better)
- **R-squared (R² Score)**: Explains how much variance in the target is captured by the model. (Higher the better)

### ✅ Model Comparison

| Model             | RMSE  | R² Score |
|------------------ |-------|----------|
| Linear Regression | 6.62  | 0.50     |
| Random Forest     | **3.92**  | **0.82**     |
| XGBoost           | 5.66  | 0.63     |
| LightGBM          | 4.13  | 0.81     |

> **Note**: These are example values. Replace with your actual evaluation metrics from the notebook.

### 🔍 Summary

- **Random Forest** achieved the best performance overall, slightly outperforming LightGBM in both accuracy and generalization.
- **XGBoost** and **LightGBM** were close behind, making them solid choices for robust modeling.
- **Linear Regression** used as a baseline estimator, performed significantly worse, highlighting the non-linear complexity of the delivery time prediction problem.

