<div align="center">

# 🌸 Iris Flower Classification

### K-Nearest Neighbors · Scikit-learn · Python

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-Educational-blue?style=for-the-badge)]()

*DecodeLabs AI · Project 2 · Batch 2026*

</div>

---

## 📌 Overview

A beginner-friendly supervised machine learning project that classifies Iris flowers into **three species** using the **K-Nearest Neighbors (KNN)** algorithm — demonstrating the complete ML pipeline from raw data to evaluation.

---

## 🌸 Dataset at a Glance

| Property | Value |
|:---|:---:|
| 🔢 Samples | 150 |
| 📐 Features | 4 |
| 🏷️ Classes | 3 |

**Features:** Sepal length · Sepal width · Petal length · Petal width

**Classes:** `Setosa` · `Versicolor` · `Virginica`

---

## ⚙️ ML Pipeline

```
Iris Dataset  →  Train/Test Split  →  Feature Scaling  →  KNN (K=5)  →  Evaluation
   150 samples       80% / 20%         StandardScaler      model.fit()    Accuracy · F1
```

---

## 🚀 Quick Start

```powershell
# 1. Create & activate virtual environment
python -m venv venv
.\venv\Scripts\Activate.ps1

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run
python main.py
```

---

## 📊 Expected Output

```
Dataset loaded successfully!

--- Dataset Information ---
Number of samples: 150
Number of features: 4

--- Data Split ---
Training samples: 120
Testing samples: 30

Feature scaling completed!
KNN model created! (K = 5)
Model training completed!
Predictions completed!

--- Model Accuracy ---
Accuracy: ~1.0 (100%)

--- Confusion Matrix ---
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]

--- Classification Report ---
              precision  recall  f1-score
    setosa       1.00     1.00     1.00
versicolor       1.00     1.00     1.00
 virginica       1.00     1.00     1.00
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|:---|:---|
| `Python` | Core language |
| `scikit-learn` | ML library |
| `StandardScaler` | Feature normalization |
| `KNeighborsClassifier` | Classification algorithm |

---

## 📁 Project Structure

```
AI-Iris-Classification/
├── main.py              ← ML implementation
├── requirements.txt     ← Dependencies
└── README.md            ← Documentation
```

> ⚠️ Add `venv/` to `.gitignore` before pushing to GitHub.

---

## 📚 Concepts Covered

`Supervised Learning` · `Classification` · `Train/Test Split` · `Feature Scaling` · `KNN` · `Confusion Matrix` · `Precision` · `Recall` · `F1 Score`

---

<div align="center">

Made with ❤️ by **P. Nanda Kishore** · B.Tech AI & ML

*DecodeLabs Industrial Training Kit · Project 2*

</div>
