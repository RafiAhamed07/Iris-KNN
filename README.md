# 🌸 KNN Iris Classification

This project demonstrates a simple implementation of the **K-Nearest Neighbors (KNN)** algorithm on the classic **Iris dataset** using Python and scikit-learn. The goal is to classify iris flowers into three species based on petal and sepal measurements.

---




---

## 🧠 What is KNN?

**K-Nearest Neighbors** is a supervised machine learning algorithm that classifies data points based on the majority class among their k-nearest neighbors in the training set.

---

## 📊 Dataset

**Iris Dataset** (from `sklearn.datasets`)  
- 150 samples, 4 features each  
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- Targets:
  - 0 = Setosa
  - 1 = Versicolor
  - 2 = Virginica

---

## 🚀 How It Works

1. **Load** the dataset from `sklearn`
2. **Split** into training and test sets (70:30)
3. **Train** the KNN model with a user-defined `k` value
4. **Evaluate** using accuracy, confusion matrix, and classification report
5. (Optional) **Visualize** error rate for various `k` values

---

## 📦 Requirements

Install dependencies using:

```bash
pip install numpy pandas pandas scikit-learn

```

## 🧪 How to Run

1. Open the notebook:
```bash
jupyter notebook "KNN Iris.ipynb"

```
2. Run all cells to:

   - Load data

   - Train the KNN model

   - Evaluate performance

   - Visualize error for different k values


