# 📩 SMS Spam Detection System

An end-to-end Machine Learning and Natural Language Processing (NLP) project that classifies text messages as either **Spam 🚨** or **Ham (Legitimate) ✅**. The project performs data cleaning, feature extraction using **TF-IDF**, evaluates 6 different ML models, and features an interactive desktop GUI built with **Tkinter**.

---

## 📌 Key Features

* **Data Cleaning & Preprocessing:** Handles missing values, removes duplicates, renames columns, and extracts message length features.
* **Text Vectorization:** Converts text messages into numerical features using **TF-IDF Vectorizer** with English stop-words removal.
* **Multi-Model Training:** Evaluates 6 distinct classification models to compare accuracy.
* **Interactive GUI:** Built using **Tkinter** to allow users to input any message and see real-time predictions from all 6 models simultaneously.

---

## 📊 Models & Performance Comparison

| Model | Accuracy |
| :--- | :---: |
| **SVM (LinearSVC)** 🏆 | **98.26%** |
| **XGBoost** | **97.39%** |
| **Random Forest** | **97.29%** |
| **Naive Bayes (MultinomialNB)** | **96.62%** |
| **Logistic Regression** | **96.42%** |
| **Decision Tree** | **96.42%** |

> **Result:** Linear **SVM** achieved the highest accuracy among all tested classifiers.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Libraries:**
  * `pandas` – Data Manipulation & Analysis
  * `scikit-learn` – Model Training & Vectorization
  * `xgboost` – Gradient Boosting Model
  * `tkinter` – Graphical User Interface (GUI)

---

## ⚙️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/SMS-Spam-Detection-ML.git](https://github.com/YOUR_USERNAME/SMS-Spam-Detection-ML.git)
   cd SMS-Spam-Detection-ML
