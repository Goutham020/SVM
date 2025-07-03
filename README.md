# 🎯 Task 7 - SVM Classifier on Breast Cancer Dataset

## 📁 Dataset
- File: `breast-cancer.csv`
- Features: Cell shape, size, texture, etc.
- Target: Diagnosis (M = Malignant, B = Benign → encoded as 1 & 0)

## 🔍 Objective
Build SVM models (linear and RBF) to classify breast cancer using scikit-learn.

## 📊 Workflow
- Load and preprocess data
- Encode categorical labels
- Standardize features
- Train linear and RBF SVMs
- Tune `C` and `gamma` using GridSearchCV
- Visualize decision boundaries using PCA (2D)

## 🧪 Results
- RBF Accuracy (Cross-Validated): ~98%
- Best Params (via GridSearch): C = 1, gamma = 0.01
- Decision boundary plotted using PCA

## 📌 How to Run
```bash
pip install pandas numpy scikit-learn matplotlib
python svm_breast_cancer.py
