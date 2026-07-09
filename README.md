# 🩺 Diabetes Prediction using Machine Learning

This project demonstrates how to build a machine learning model to predict whether a patient has diabetes based on medical diagnostic measurements. The notebook follows a complete machine learning workflow, including data exploration, preprocessing, handling class imbalance, model training, and evaluation.

---

## 📌 Features

- Exploratory Data Analysis (EDA)
- Data visualization with Matplotlib and Seaborn
- Feature standardization
- Class imbalance handling using SMOTE
- Train/Test split
- Logistic Regression model
- Model evaluation using classification metrics
- Confusion matrix visualization

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn (SMOTE)
- Jupyter Notebook

---

## 📚 Libraries

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
```

---

## 📂 Project Structure

```
diabetes-prediction/
│
├── diabetes.csv
├── main.ipynb
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

The project uses the **Pima Indians Diabetes Dataset**, which contains several medical measurements used to predict whether a patient has diabetes.

Some of the features include:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

The target variable indicates whether the patient has diabetes.

---

## ⚙️ Machine Learning Workflow

The notebook covers:

- Loading and exploring the dataset
- Data visualization
- Feature scaling using `StandardScaler`
- Balancing the dataset with **SMOTE**
- Splitting the data into training and testing sets
- Training a **Logistic Regression** model
- Making predictions
- Evaluating model performance

---

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

---

## 🚀 Getting Started

Install them manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
main.ipynb
```

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Perform exploratory data analysis
- Prepare data for machine learning
- Handle imbalanced datasets with SMOTE
- Train a Logistic Regression classifier
- Evaluate a classification model using standard metrics

---

⭐ If you found this project useful, consider giving it a star!
