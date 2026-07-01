# 🩺 Diabetes Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a person has diabetes based on their health, lifestyle, and demographic information using Machine Learning classification algorithms.

The project follows a complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and prediction.

---

## 🎯 Problem Statement

Diabetes is one of the most common chronic diseases worldwide. Early prediction can help individuals seek timely medical advice and improve disease management.

The objective of this project is to build a Machine Learning model that predicts whether a person has diabetes using various health-related attributes.

---

## 🧠 Machine Learning Type

* **Learning Type:** Supervised Learning
* **Problem Type:** Binary Classification

---

## 📂 Dataset

The dataset contains **700,000 records** and **26 columns**, including:

### Features

* Age
* Gender
* BMI
* Waist-to-Hip Ratio
* Blood Pressure
* Heart Rate
* Cholesterol Levels
* Triglycerides
* Physical Activity
* Diet Score
* Sleep Hours
* Smoking Status
* Alcohol Consumption
* Family History of Diabetes
* Hypertension History
* Cardiovascular History
* Education Level
* Income Level
* Employment Status
* Ethnicity

### Target Variable

`diagnosed_diabetes`

* **0** → No Diabetes
* **1** → Diabetes

---

## 🚀 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Feature Engineering
7. Data Preprocessing
8. Train-Test Split
9. Feature Scaling
10. Model Training
11. Prediction
12. Model Evaluation
13. Feature Importance
14. Conclusion

---

## 🛠 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 🤖 Machine Learning Algorithms

The project can be implemented using:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* Naive Bayes

The primary implementation uses the **Random Forest Classifier**.

---

## 📊 Model Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📁 Project Structure

```text
Diabetes-Prediction/
│
├── Diabetes train.csv
├── Diabetes_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Diabetes-Prediction.git
```

2. Navigate to the project folder.

```bash
cd Diabetes-Prediction
```

3. Install the required libraries.

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook.

```bash
jupyter notebook
```

5. Run all notebook cells.

---

## 📈 Results

The trained model predicts whether a patient has diabetes based on health and lifestyle information. Model performance is measured using classification metrics such as accuracy, precision, recall, and F1-score.

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Cross-validation
* Feature selection
* Ensemble learning
* Model deployment using Flask or FastAPI
* Interactive web application using Streamlit

---

## 👨‍💻 Author

**Jenin**

Post Graduate Diploma in Data Science
B.Sc. Computer Science

---

## 📜 License

This project is intended for educational and learning purposes.
