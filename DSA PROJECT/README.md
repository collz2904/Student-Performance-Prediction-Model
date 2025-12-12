# Student Performance Prediction System

Data Science Project: Predicting Student Performance using classification models.
This project implements a comprehensive Machine Learning pipeline to identify factors influencing student academic success.

## Project Goal

To build a machine learning model that accurately predicts the final performance of students based on demographic, social, and academic features. The outcome of the project provides valuable insights into potential intervention points for students at risk.

## Dataset

* **Dataset:** Student Performance Prediction Dataset by Amr Maree.
* **Target Variable:** The final academic status (e.g., Pass/Fail or grade level) is defined as the target variable for prediction.

## Project Outline (5 Weeks)

### Week 1 & 2: Data Exploration and Cleaning

* **Objective:** Understand the problem, clean the dataset, and identify feature relationships.
* **Initial Steps:** Load dataset and establish the target variable.
* **Cleaning:** Thorough checks for **missing values, outliers, duplicates**, and **incorrect data types** were performed using NumPy and Seaborn.
* **Preparation:** Applied **encoding** (e.g., Label/One-Hot) and transformations to normalize numerical distributions where necessary.

### Week 3: Feature Engineering and Selection

* **Objective:** Enhance predictive power through new features and selecting the most significant variables.
* **Engineering:** Created domain-specific and non-linear features.
* **Selection:** Implemented **Principal Component Analysis (PCA)** for dimensionality reduction.
* **Approach:** Used statistical methods for variable selection and checked for non-linear feature interactions.

### Week 4: Model Building

* **Objective:** Train and evaluate a variety of classification models.
* **Training:** The data was split into **Train/Test** sets (70/30 split with random\_state=42).
* **Algorithms Implemented:**
    * **K-Nearest Neighbors (KNN)**
    * **Decision Trees (DT)**
    * **Random Forests (RF)**
    * **Support Vector Machines (SVM)**
    * **Logistic Regression (LR)**
    * **Naive Bayes**
* **Optimization:** Non-linear ensemble models (e.g., BaggingClassifier) were also used for improved performance.

### Week 5: Model Evaluation and Reporting

* **Objective:** Evaluate model performance, analyze results, and report key findings.
* **Metrics Used:**
    * **Accuracy Score**
    * **F1 Score**
    * **ROC Curve and AUC (Area Under the Curve)**
    * **Confusion Matrix**
* **Final Output:** Key findings and a **deployment recommendation** were provided.