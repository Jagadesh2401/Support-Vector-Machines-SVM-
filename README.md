# Task 7: Support Vector Machines (SVM)

## 📌 Objective

This task focuses on implementing Support Vector Machines (SVM) using both linear and non-linear (RBF) kernels for binary classification. The dataset used is the Breast Cancer dataset.

## 🛠️ Tools & Libraries

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

## 🔗 Dataset Used

[Breast Cancer Dataset (Kaggle)](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)

## 📁 Files

* `svm_classification_task7.ipynb` or `.py`: Full code implementation
* `data.csv`: Dataset (replace with the appropriate filename)
* `README.md`: Task explanation and results

## 🚀 Steps Performed

1. **Load & Explore Dataset**
2. **Preprocess Data**: Drop irrelevant columns, encode target
3. **Split & Scale Data**
4. **Train Linear SVM**
5. **Train RBF SVM**
6. **Evaluate Models (Confusion Matrix & Classification Report)**
7. **Tune Hyperparameters using GridSearchCV**
8. **Visualize Decision Boundaries using PCA**

## 📊 Results

### Linear SVM

* Accuracy: \~96%
* Precision/Recall/F1: High for both classes

### RBF SVM

* Accuracy: \~97%
* Improved boundary handling on non-linear data

### Best Parameters (GridSearchCV):

* `C=10`
* `gamma=0.1`
* `kernel=rbf`
  
