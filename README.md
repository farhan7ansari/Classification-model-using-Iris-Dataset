# Classification-model-using-Iris-Dataset

## 📘 Overview

This repository demonstrates the application of machine learning algorithms to classify iris flower species using the well-known Iris dataset. The dataset comprises 150 samples from three species of iris flowers: Setosa, Versicolor, and Virginica. Each sample includes four features: sepal length, sepal width, petal length, and petal width, all measured in centimeters.

The primary objective is to build and evaluate classification models to accurately predict the species of iris flowers based on these features.

---

## 🗂️ Repository Structure

-training_data.xlsx ── Dataset used for training the models
-testing_data.xlsx ── Dataset used for testing/evaluation
-model_on_iris_classification.ipynb ── Jupyter notebook implementing the classification models

---

## 🧰 Tools & Libraries

- **Programming Language**: Python (version 3.x)
- **Libraries**:
  - `pandas` — Data manipulation and analysis
  - `numpy` — Numerical operations
  - `matplotlib` / `seaborn` — Data visualization
  - `scikit-learn` — Machine learning algorithms and utilities
  - `openpyxl` — Reading and writing Excel files

---

## 🔍 Methodology

1. **Data Loading**: Import the Iris dataset into a Pandas DataFrame from the provided Excel files.
2. **Data Preprocessing**:
   - Handle missing values (if any)
   - Encode categorical labels (if necessary)
   - Split the dataset into training and testing sets
3. **Model Building**:
   - Implement various classification algorithms, such as:
     - Logistic Regression
     - Decision Trees
     - Support Vector Machines (SVM)
     - K-Nearest Neighbors (KNN)
   - Train models using the training dataset
4. **Model Evaluation**:
   - Evaluate model performance using metrics like accuracy, precision, recall, and F1-score
   - Visualize results using confusion matrices and classification reports
5. **Model Comparison**:
   - Compare the performance of different models to identify the best-performing algorithm

---

## 🧪 How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/farhan7ansari/Classification-model-using-Iris-Dataset.git
   cd Classification-model-using-Iris-Dataset
