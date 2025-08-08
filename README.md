# 🩺 Breast Cancer Classification with Logistic Regression

This project implements a binary classifier using **Logistic Regression** to predict whether breast cancer samples are **malignant** or **benign**, using the Breast Cancer Wisconsin dataset.

---

## 📌 Project Overview

- **Task**: Binary classification of breast cancer tumors.
- **Model**: Logistic Regression.
- **Dataset**: Breast Cancer Wisconsin dataset (scikit-learn version).
- **Metrics**: Confusion matrix, precision, recall, ROC-AUC, accuracy.
- **Libraries**: Scikit-learn, Pandas, Matplotlib, Seaborn.

---

## 🔨 Steps Performed

1️⃣ Loaded and explored the dataset.  
2️⃣ Split into training and testing sets.  
3️⃣ Scaled features using `StandardScaler`.  
4️⃣ Trained a Logistic Regression model.  
5️⃣ Evaluated performance:
   - Confusion matrix
   - Precision, recall, accuracy
   - ROC-AUC curve  
6️⃣ Tuned decision threshold.  
7️⃣ Visualized the sigmoid function.

---

## 📊 Evaluation Results

- **Confusion Matrix**: [[41 2]
                         [1 70]]
- **Precision**: 0.9722  
- **Recall**: 0.9859  
- **ROC-AUC**: 0.9974  
- **Accuracy**: 0.9737  

These results show that the model performs with **high precision and recall**, indicating excellent predictive capability for both malignant and benign cases.

---

## 📈 Visualizations

- ROC Curve shows excellent separability (AUC ~0.997).
- Sigmoid function plotted for understanding logistic regression decision boundaries.

---

