# PIMA Diabetes Classification

## Overview

This project investigates the use of machine learning and deep learning techniques for diabetes prediction using the PIMA Indians Diabetes Dataset.

The objective was to compare multiple classification approaches, evaluate model performance, and analyze the impact of preprocessing and class imbalance handling techniques on predictive accuracy.

The project combines exploratory data analysis, statistical analysis, traditional machine learning models, and neural networks.

---

## Dataset

The analysis was performed using the PIMA Indians Diabetes Dataset.

Dataset characteristics:

* 768 observations
* 8 clinical features
* Binary target variable (Diabetes / No Diabetes)

Features include:

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

Target:

* Outcome = 1 (Diabetes)
* Outcome = 0 (No Diabetes)

---

## Project Objectives

The project aimed to:

* Explore relationships between medical indicators and diabetes diagnosis.
* Identify important predictive features.
* Evaluate multiple machine learning algorithms.
* Address class imbalance using SMOTE.
* Compare traditional ML approaches with neural network architectures.

---

## Data Preprocessing

The preprocessing stage included:

* Missing value detection
* Data cleaning
* Feature scaling
* Exploratory data analysis
* Correlation analysis
* Class distribution analysis

---

## Exploratory Data Analysis

Several visualizations were created to better understand the dataset.

### Correlation Analysis

Correlation analysis was performed to identify relationships between variables.

<img width="895" height="806" alt="image" src="https://github.com/user-attachments/assets/63328481-b0b8-47c0-be3f-59b566682f45" />


### Feature Distribution Analysis

Distribution plots were used to examine feature behavior across diabetic and non-diabetic groups.

<img width="1002" height="918" alt="image" src="https://github.com/user-attachments/assets/ae919c68-2385-484a-b1d3-92e56b471b27" />


---

## Machine Learning Models

Several classification approaches were evaluated.

### Logistic Regression

Used as a baseline classification model.

### Decision Tree

Evaluated the performance of a tree-based approach.

### Decision Tree + SMOTE

SMOTE oversampling was applied to address class imbalance and improve minority class representation.

### Multi-Layer Perceptron (MLP)

A neural network architecture used for non-linear classification.

### CNN1D

A one-dimensional convolutional neural network adapted for tabular medical data.

---

## Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Cross Validation

The objective was to compare model stability and predictive performance.

<img width="855" height="654" alt="image" src="https://github.com/user-attachments/assets/1dd2137b-b862-4c90-b055-15724ed1c4d8" />


---

## Results

The comparison demonstrated differences in performance between traditional machine learning algorithms and neural network approaches.

Key findings included:

* Glucose was among the strongest predictive variables.
* Data preprocessing significantly influenced performance.
* SMOTE improved minority class representation.
* Neural networks achieved competitive classification results compared to traditional ML methods.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow
* Keras
* Matplotlib
* Seaborn
* Imbalanced-Learn (SMOTE)


