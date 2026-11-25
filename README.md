# AI-Powered Sleep Health Prediction

## 📌 Project Overview

This project explores sleep health and lifestyle data using machine learning to classify sleep disorders. It focuses on analyzing lifestyle-related features and comparing different classification models to understand their performance in predicting sleep disorder categories.

The project is developed using Python and machine learning techniques as part of my Data Science learning journey.

## 🎯 Objectives

- Explore and understand sleep health and lifestyle data.
- Perform data cleaning and preprocessing.
- Analyze relevant features and patterns.
- Train and compare multiple machine learning classification models.
- Evaluate model performance using appropriate metrics.
- Explore prediction probabilities and decision thresholds.

## 📂 Dataset

**Dataset:** Sleep Health and Lifestyle Dataset

The dataset includes features related to:

- Age
- Gender
- Occupation
- Sleep Duration
- Quality of Sleep
- Physical Activity Level
- Stress Level
- BMI Category
- Blood Pressure
- Heart Rate
- Daily Steps
- Sleep Disorder

### Data Preprocessing

- Exploratory Data Analysis (EDA)
- Handling missing values
- Feature preprocessing
- Removing irrelevant columns
- Encoding categorical features
- Train-test splitting
- Feature scaling using StandardScaler

## 🤖 Machine Learning Models

The following classification models have been evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

Models are compared using cross-validation and test-set evaluation.

## 📊 Model Evaluation

Evaluation techniques used:

- Accuracy
- Confusion Matrix
- Classification Report
- Stratified K-Fold Cross-Validation
- Mean CV Accuracy
- Standard Deviation
- Prediction Probability Analysis
- Decision Threshold Analysis

### Initial Model Comparison

| Model | Mean CV Accuracy | Test Accuracy |
|---|---:|---:|
| Logistic Regression | 88.63% | 83.87% |
| KNN | 87.83% | 77.42% |
| Decision Tree | 85.43% | 87.10% |
| Random Forest | 84.60% | 90.32% |

*These are initial experimental results. Further evaluation, including ROC-AUC analysis, threshold analysis, and final model selection, is ongoing.*

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 📁 Repository Contents

- `project_health (3).ipynb` — Jupyter notebook containing data analysis, preprocessing, model training, evaluation, and experiments.

## ⚠️ Limitations

- The dataset contains a limited number of observations.
- Many records have missing sleep disorder labels and were excluded from the initial supervised learning analysis.
- The model currently focuses on two classes: Insomnia and Sleep Apnea.
- The results may not generalize to real-world populations.
- Predictions are based on the available dataset and features.
- This project is educational and experimental; it is not a medical diagnostic tool.

## 🚧 Project Status

Currently working on:

- ROC-AUC analysis
- Model evaluation and error analysis
- Probability-based prediction analysis
- Decision threshold comparison
- Final model selection
- Model saving and deployment planning

## 👨‍💻 Author

**Anurag**

BCA – Artificial Intelligence

Aspiring Data Scientist | Machine Learning Enthusiast
