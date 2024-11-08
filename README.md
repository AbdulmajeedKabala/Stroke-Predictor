# Stroke Predictor

This repository contains a machine learning model to predict the likelihood of strokes based on medical and demographic attributes. The model achieves high accuracy through hyperparameter tuning and extensive data preprocessing. 

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Overview

The goal of this project is to develop a classification model to predict stroke likelihood in patients based on features such as age, gender, BMI, and glucose level. The model uses logistic regression and decision tree classifiers, fine-tuned via GridSearchCV to enhance accuracy. 

## Dataset

The dataset used in this project contains **5,000+ entries** with **12 features** per entry, including:
- Age
- Gender
- Hypertension
- Heart disease
- BMI
- Average glucose level
- ...and more.

## Model

The project includes:
1. Data preprocessing: Outlier removal, feature scaling, and normalization.
2. Model selection: Decision Tree Classifier and Logistic Regression models.
3. Hyperparameter optimization: Fine-tuning using `GridSearchCV` for optimal performance.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/stroke-prediction.git
   cd stroke-prediction
1. **Set up a virtual environment (optional but recommended)**
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
1. **Install the required packages**:
   pip install -r requirements.txt
   
## Usage

Prepare the dataset:
Ensure your dataset (stroke_data.csv) is in the project directory or update the file path in the code.

Run the model:
To run the code, execute the main script:
python stroke_model.py

View Results:
After running, you’ll see the best model parameters and accuracy on the test set printed in the console.

## Results
Best Model Parameters: The best parameters found through GridSearchCV will be displayed in the console.
Model Accuracy: The accuracy on the test set after hyperparameter tuning is approximately 94%.



