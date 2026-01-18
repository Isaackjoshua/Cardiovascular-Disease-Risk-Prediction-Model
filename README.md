# Cardiovascular Disease Risk Prediction Model

A machine learning project focused on predicting the risk of cardiovascular disease using clinical and lifestyle data.  
The project compares multiple classification algorithms and emphasizes handling real-world challenges such as class imbalance, noise, and missing values.

---

## 📌 Project Overview

Cardiovascular diseases (CVDs) are among the leading causes of death worldwide. Early risk prediction can support preventive healthcare decisions and reduce mortality rates.

This project builds and evaluates several machine learning classification models to predict whether a patient is at risk of developing cardiovascular disease based on medical and demographic features.

---

## 🎯 Objectives

- Predict cardiovascular disease risk using supervised learning
- Compare the performance of different classification models
- Handle real-world data challenges such as:
  - Class imbalance
  - Noisy features
  - Missing values
- Evaluate models using clinically meaningful metrics

---

## 🧠 Models Implemented

The following classification models are trained and evaluated:

- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree Classifier**

Each model is tuned and evaluated under the same data conditions to allow fair comparison.

---

## 📊 Dataset

- **Type:** Structured tabular healthcare data  
- **Features may include:**
  - Age
  - Gender
  - Blood pressure
  - Cholesterol levels
  - BMI
  - Smoking status
  - Physical activity
- **Target Variable:**  
  - `0` → No cardiovascular disease  
  - `1` → Presence of cardiovascular disease  

> ⚠️ Dataset used is for educational and research purposes only and **not** for clinical diagnosis.

---

## 🛠️ Data Preprocessing

Key preprocessing steps include:

- Handling missing values
- Feature scaling (for distance-based models like KNN and SVM)
- Encoding categorical variables
- Addressing class imbalance (e.g., resampling or class weighting)
- Noise analysis to simulate real-world healthcare data inconsistencies

---

## 📈 Model Evaluation Metrics

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Curve
- Confusion Matrix

Special emphasis is placed on **Recall**, as false negatives in healthcare can be critical.

---

## 🚀 Results & Insights

- Performance varies across models depending on data preprocessing and imbalance handling.
- Simpler models (e.g., Logistic Regression) provide strong interpretability.
- More complex models (e.g., SVM, Decision Tree) capture non-linear patterns but require careful tuning.
- Class imbalance significantly impacts prediction performance if not handled properly.

Detailed evaluation results and comparisons are provided in the notebooks/scripts.

---

## 🧪 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter ---

## 🧠 Future Improvements

- Incorporate ensemble methods (Random Forest, Gradient Boosting)
- Apply advanced imbalance techniques (SMOTE, ADASYN)
- Perform feature importance analysis
- Experiment with deep learning models
- Deploy model as a web API

---

## ⚠️ Disclaimer

This project is intended **for educational and research purposes only**.  
It should **not** be used as a medical diagnostic tool.

---

## 👤 Author

**Isaack Joshua**  
Machine Learning & Software Engineering Enthusiast  

- GitHub: [Isaackjoshua](https://github.com/Isaackjoshua)
- LinkedIn: https://www.linkedin.com/in/isaack-joshua-7277ba29a/

---

⭐ If you find this project useful, consider giving it a star!

