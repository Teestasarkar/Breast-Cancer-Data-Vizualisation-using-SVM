# Breast Cancer Classification using SVM

## Overview
This project implements a **Support Vector Machine (SVM)** classifier to predict whether a tumor is **malignant** or **benign** using the **Breast Cancer Wisconsin dataset**. The goal is to create a simple, effective machine learning model and evaluate its performance with standard metrics.

---

## Dataset
- Source: `sklearn.datasets.load_breast_cancer()`
- Features: 30 numeric medical measurements (e.g., radius, texture, smoothness)
- Target: Binary classification  
  - 0 → Malignant  
  - 1 → Benign
- Total samples: 569

---

## Steps in the Project
1. **Data Loading & Exploration**
   - Loaded dataset into a Pandas DataFrame.
   - Checked first few rows and basic statistics.

2. **Data Preprocessing**
   - Split data into **training (80%)** and **testing (20%)** sets.
   - Standardized features using `StandardScaler`.

3. **Model Training**
   - Trained an **SVM classifier** (`SVC`) on the training set.
   - Used the **RBF kernel** (default) for classification.

4. **Model Evaluation**
   - Predicted the test set labels.
   - Calculated **accuracy**, **confusion matrix**, and **classification report** (precision, recall, F1-score).

5. **Visualization**
   - Plotted confusion matrix for intuitive evaluation.
   - Optional: feature importance using linear SVM.

---

## How to Run
1. Open the project in **Google Colab** or **Jupyter Notebook**.
2. Run all cells in order:
   - Load dataset
   - Preprocess data
   - Train SVM model
   - Evaluate results
   - Visualize (optional)
3. Check the output metrics and plots.

---

## Results
- Accuracy: ~97–98% (may vary slightly depending on train/test split)
- Confusion matrix shows most predictions are correct.
- ROC curve and classification report validate model performance.

---

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- joblib (optional, for saving the model)

---

## Author
- Your Name  
- Project submitted as part of ML coursework / mini project

---

