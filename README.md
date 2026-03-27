# 📊 Support Vector Machines (SVM) on Iris Dataset

## 📌 Project Overview

This project demonstrates the application of **Support Vector Machines (SVM)** for multi-class classification using the **Iris dataset**. It focuses on comparing different kernel functions and analysing their impact on classification performance.

The study evaluates **Linear, Polynomial, and RBF kernels** and visualises model behaviour using multiple techniques such as PCA, ROC curves, and decision boundaries.

---

## 🎯 Objectives

* Understand how SVM works for classification
* Compare performance of different kernel functions
* Evaluate models using standard metrics
* Visualise classification results and decision boundaries

---

## 📂 Dataset

The project uses the **Iris dataset**, which contains:

* 150 samples
* 3 classes: *Setosa, Versicolor, Virginica*
* 4 features:

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width

---

## ⚙️ Methodology

### 🔹 Data Preprocessing

* Train-test split (80:20)
* Stratified sampling
* Feature scaling using StandardScaler

### 🔹 Models Used

* Linear SVM
* Polynomial SVM
* RBF SVM

### 🔹 Evaluation Metrics

* Accuracy
* Confusion Matrix
* ROC Curve & AUC

---

## 📈 Results

| Model      | Accuracy |
| ---------- | -------- |
| Linear SVM | 100%     |
| Polynomial | 90%      |
| RBF        | 97%      |

### 🔍 Key Insights

* Linear SVM performed best due to near-linear separability
* Polynomial kernel showed lower performance (possible overfitting)
* RBF kernel handled non-linearity but did not outperform linear

---

## 📊 Visualisations Included

* Class distribution plot
* Feature scatter plots
* Kernel comparison chart
* Confusion matrices
* PCA visualisation
* Decision boundary plots
* ROC curves

---

## 📉 PCA Analysis

* Reduced dataset to 2 dimensions
* Clear separation for *Setosa*
* Overlap observed between *Versicolor* and *Virginica*

---

## 🧠 Conclusion

* SVM is highly effective for classification tasks
* Simpler models can outperform complex ones when data is linearly separable
* Kernel selection plays a critical role in performance

---

## ⚠️ Limitations

* Sensitive to feature scaling
* Requires careful parameter tuning
* Computationally expensive for large datasets

---

## 🚀 Future Improvements

* Hyperparameter tuning (GridSearchCV)
* Testing on larger datasets
* Comparing with other algorithms (e.g., Random Forest, KNN)

---

## 📚 References

* Cortes & Vapnik (1995) – Support Vector Machines
* Bishop (2006) – Pattern Recognition
* Géron (2019) – Hands-On ML
* Han et al. (2011) – Data Mining
---

## ⭐ If you found this useful, consider giving it a star!
