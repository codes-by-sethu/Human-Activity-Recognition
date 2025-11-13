# Human Activity Recognition: Dimensionality Reduction & Classification

This project explores **dimensionality reduction** and **feature selection** techniques to classify human activities from smartphone sensor data using the **HAR dataset**.

---

## 📝 Project Description

The goal is to reduce 561 sensor features and evaluate their impact on classification using a **Random Forest classifier**. Techniques applied include:

* **Dimensionality Reduction:**

  * PCA: Preserves variance
  * t-SNE: Non-linear visualization
  * LDA: Maximizes class separability

* **Feature Selection:**

  * SelectKBest: Top features via ANOVA F-value
  * RFE: Recursive elimination using Logistic Regression

**Finding:** LDA-reduced data yields the best classification accuracy.

---

## 📊 Results

* LDA: Best class separation and predictive performance
* PCA: Good for compression, limited class separation
* t-SNE: Excellent visualization, not suited for modeling

---

## ⚙️ Technologies Used

* Python, Pandas, NumPy, Scikit-learn
* Random Forest classifier
* Visualization libraries: Matplotlib, Seaborn

---

## 📂 Usage

1. Load the HAR dataset (`X_train.txt`, `y_train.txt`).
2. Preprocess data (scaling, imputation).
3. Apply dimensionality reduction or feature selection.
4. Train and evaluate Random Forest classifier.
