# 🩺 Diabetes Prediction using Logistic Regression

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/ML-scikit--learn-orange)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

This project applies logistic regression to predict whether a person has diabetes based on medical and physiological attributes using the **Pima Indians Diabetes Dataset**. It also visualizes the sigmoid function to illustrate how logistic regression interprets data.

---

## 📁 Project Files

- `diabeties.csv` – Dataset used for training and testing the model
- `diabetes_prediction.py` – Main script with model training, evaluation, and sigmoid plot
- `README.md` – Project documentation

---

## 🧪 Dataset Features

| Feature                     | Description                                 |
|----------------------------|---------------------------------------------|
| Pregnancies                | Number of times pregnant                    |
| Glucose                    | Plasma glucose concentration                |
| BloodPressure              | Diastolic blood pressure (mm Hg)            |
| SkinThickness              | Triceps skin fold thickness (mm)           |
| Insulin                    | 2-Hour serum insulin (mu U/ml)             |
| BMI                        | Body mass index (weight in kg/m²)          |
| DiabetesPedigreeFunction   | Diabetes pedigree function                 |
| Age                        | Age (years)                                |
| Outcome                    | Class label (0: No diabetes, 1: Diabetes)   |

---

## 🧠 Model Overview

- **Model Type**: Logistic Regression (Binary Classification)
- **Library**: `scikit-learn`
- **Target Variable**: `Outcome` (0 or 1)

---

## ⚙️ Workflow

1. Load and display the data
2. Split into features (`X`) and target (`y`)
3. Train/test split (80%/20%)
4. Train a Logistic Regression model
5. Predict on test data
6. Evaluate using accuracy, confusion matrix, classification report
7. Visualize the sigmoid function

---

## 📈 Evaluation Sample Output

       0       0.33      1.00      0.50         1
       1       1.00      0.33      0.50         3

> Note: Results may vary depending on the sample size and split randomness. A small test set may not reflect model generalizability.

---

## 📉 Visualization

The script plots the **Sigmoid Function** used by logistic regression to map input values between 0 and 1.

![Sigmoid Function](assets/sigmoid_plot.png) <!-- Replace with actual image path if added -->

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/diabetes-logistic-regression.git
cd diabetes-logistic-regression
