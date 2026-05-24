# 🚢 Titanic Machine Learning Pipeline

This project is a complete end-to-end machine learning workflow applied to the Titanic dataset.  
The goal is to predict whether a passenger survived or not based on different features.

---

## 📌 Problem Statement
The Titanic dataset contains information about passengers such as age, sex, ticket class, etc.  
The objective is to build a classification model that predicts survival.

---

## 📊 Dataset
The dataset is taken from Kaggle Titanic competition:
https://www.kaggle.com/c/titanic

Features include:
- PassengerId
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

---

## ⚙️ Workflow

The project follows an end-to-end ML pipeline:

### 1. Data Understanding
- Exploring dataset structure
- Checking missing values
- Understanding feature types

### 2. Data Cleaning
- Handling missing values (Age, Embarked)
- Removing duplicates (if any)

### 3. Feature Engineering
- Creating new features like FamilySize
- Extracting useful patterns from data

### 4. Encoding
- Label Encoding for binary features (Sex)
- One-Hot Encoding for categorical features (Embarked)

### 5. Model Building
- Logistic Regression
- Decision Tree
- Random Forest

### 6. Evaluation
- Accuracy score
- Confusion matrix
- Cross-validation

---

## 📈 Results
Best performing model: Random Forest Classifier  
Accuracy: ~ (add your score here)

---

## 🧠 Key Learnings
- Importance of handling missing values correctly
- Difference between Label Encoding and One-Hot Encoding
- Feature engineering impact on performance
- Building a full ML pipeline from scratch

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
python main.py
