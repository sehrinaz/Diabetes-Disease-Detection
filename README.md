# 🩺 Diabetes Disease Detection: Impact of Feature Selection & Kernels

This project investigates the impact of feature engineering and algorithm selection on diabetes prediction performance. It provides a comparative analysis using two distinct datasets with **9** and **22** features across various Machine Learning models.

---

## 📊 Comparative Analysis Overview
The primary goal of this research was to evaluate how the number of features and different kernel functions affect prediction accuracy.

### 🔹 Key Findings
* **Dataset A (9 Features):** Achieved its peak performance of **97.32%** using the **Decision Tree (DT)** algorithm.(Kaggle, Diabetes prediction dataset, https://www.kaggle.com/code
/tumpanjawat/diabetes-eda-random-forest-hp/input (2023).)
* **Dataset B (22 Features):** Reached a maximum accuracy of **85.08%** using **Support Vector Regression (SVR)** with an **RBF Kernel**. (Kaggle, Diabetes health indicators dataset,
https://www.kaggle.com/datasets/julnazz/diabetes-health-indicators-dataset/data (2021).)
* **Kernel Comparison:** Evaluated Linear, Polynomial, RBF, and Sigmoid kernels. The **RBF (Radial Basis Function) kernel** consistently outperformed others across both datasets.

---

## 🛠 Evaluated Algorithms
The following machine learning models were implemented and compared:
* **SVM** (Support Vector Machine)
* **SVR** (Support Vector Regression)
* **KNN** (K-Nearest Neighbors)
* **GNB** (Gaussian Naive Bayes)
* **DT** (Decision Tree)
* **LR** (Logistic Regression)
* **RF** (Random Forest)

---

## 🚀 Technical Highlights
* **Feature Engineering:** Analysis of how increasing features from 9 to 22 impacts model complexity and accuracy.
* **Kernel Optimization:** Detailed testing of SVM/SVR kernels (Linear, Poly, RBF, Sigmoid).
* **Significant Result:** The study highlights that a more focused feature set (9 features) combined with Decision Trees yielded higher accuracy than a broader feature set in this specific context.

## 📂 Installation & Usage
1. Clone the repo:
   ```bash
   git clone [https://github.com/sehrinaz/Diabetes-Disease-Detection.git](https://github.com/sehrinaz/Diabetes-Disease-Detection.git)