#  Health Risk Tier Prediction Using Artificial Neural Networks

Machine Learning | Healthcare Analytics | Classification

---

##  Project Overview

This project develops and evaluates Artificial Neural Network (ANN) models to classify patients into three health risk tiers using demographic, lifestyle, and clinical data. The objective was to determine whether neural networks could improve prediction accuracy compared to a traditional Logistic Regression model.

The project demonstrates the complete machine learning pipeline, including data preprocessing, feature engineering, neural network development, hyperparameter tuning, regularization, and model evaluation.

---

##  Objective

Develop a machine learning model capable of accurately predicting patient health risk levels while comparing the performance of multiple ANN architectures against a Logistic Regression baseline.

---

##  Dataset

The dataset consists of **600 patient records** classified into **three health risk tiers**.

### Features

- Age
- BMI
- Blood Pressure
- Glucose
- Cholesterol
- Physical Activity
- Sleep Duration
- Stress Level
- Family History

---

## Tools & Technologies

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

##  Results

| Model | Accuracy |
|------|---------:|
| Logistic Regression | **71.67%** |
| ANN Configuration 1 | **77.50%** |
| ANN Configuration 2 | **80.83%** |
| ANN + L2 Regularization | **81.67%** |

### Key Findings

- ANN models consistently outperformed the Logistic Regression baseline.
- Increasing network complexity improved predictive performance.
- L2 regularization reduced overfitting and improved model generalization.
- The final ANN model achieved the highest classification accuracy.

---

##  Visualizations

This project includes:

- Learning Curve
- Confusion Matrix
- Accuracy Comparison
- Classification Metrics

---

##  Future Improvements

- Train on a larger healthcare dataset.
- Explore additional deep learning architectures.
- Address class imbalance using SMOTE.
- Deploy the model as an interactive healthcare analytics application.

