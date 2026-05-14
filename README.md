# breast-cancer-diagnostic-analysis
Data Mining project analyzing the Breast Cancer Wisconsin (Diagnostic) dataset using KNN, Perceptron, Neural Networks, SVM, and Decision Trees.



---

# 🧪 Data Mining Assignment

## 🎀 Breast Cancer Wisconsin (Diagnostic) Analysis

---

## 🎓 Course Information

📘 **Course:** Data Mining: Models, Algorithms, and Applications
👨‍🏫 **Instructor:** Dr. Ahmadi
🏫 **University:** Amirkabir University of Technology (Tehran Polytechnic)

---

# 📌 Problem Description

The **Breast Cancer Wisconsin** dataset from the **UCI Machine Learning Repository** is considered for this project.

* Features are computed from digitized images of fine needle aspirates (FNA) of breast masses.
* They describe characteristics of the **cell nuclei** present in the images.
* The target variable is **Diagnosis**: Malignant (M) or Benign (B).

🔗 **Dataset Link:**
[https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

---

# 🧩 Assignment Tasks

## 🔧 (A) Data Preparation

* Prepare the data if necessary.
* Handle missing values and noise (this dataset has **no missing values**).
* Standardize data using the **Min-Max method**.

---

## 📊 (B) Data Splitting and Confusion Matrix

* Split the data using the **Perceptron method**: 75% for training, 25% for testing.
* Construct the **confusion matrix** and explain the results.

---

## 🧠 (C) Modeling and Evaluation

* Apply the following methods:

  * **K-Nearest Neighbors (KNN)**
  * **Perceptron**
  * **Multi-Layer Neural Network (Radial Basis Function)**
  * **Support Vector Machines (SVM)**
* Use **five-fold cross-validation** to evaluate with:

  * **Accuracy**
  * **Sensitivity**
  * **Specificity**
  * **AUC (Area Under the Curve)**
* Determine which method performs best and explain why.

---

## 🌳 (D) Decision Tree and Feature Selection

* Solve part (C) again using a **Decision Tree**.
* Draw the developed tree and extract the rules.
* Use **Forward Selection** to identify the best combination of features.

---

# 📊 Dataset Overview

* 📦 **Total Records:** 569
* 📦 **Total Columns:** 32 (ID + Target + 30 features)
* 🆔 **ID Column:** Unique identifier (not used as a feature)
* 📥 **Input Features:** 30 (all continuous)
* 🎯 **Target Variable:** `Diagnosis` (M / B)
* ⚠️ **Missing Values:** None

---

# 🧾 Feature Names and Descriptions

| No.  | Attribute                  | Type        | Description                                                                                                                                                                | Units | Missing Values |
| ---- | -------------------------- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- | -------------- |
| 0    | ID                         | Categorical | Record ID                                                                                                                                                                  | -     | No             |
| 1    | Diagnosis                  | Target      | Malignant / Benign                                                                                                                                                         | -     | No             |
| 2-31 | radius1…fractal_dimension3 | Continuous  | Ten real-valued features computed for each cell nucleus: radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, fractal dimension | -     | No             |

> Features are calculated from the FNA images of cell nuclei.

---

# 📌 References

* [UCI Machine Learning Repository – Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
* K. P. Bennett and O. L. Mangasarian, *Robust Linear Programming Discrimination of Two Linearly Inseparable Sets*, Optimization Methods and Software, 1, 1992, 23-34.

می‌خوای بسازم؟
