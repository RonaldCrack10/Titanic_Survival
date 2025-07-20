# Titanic_Survival

This project uses **machine learning** to predict whether a passenger survived the Titanic disaster, based on features like age, gender, ticket class, and more. It's based on the classic [Kaggle Titanic dataset](https://www.kaggle.com/c/titanic).

## 📁 Project Structure

├── Titanic survival.ipynb Jupyter Notebook 
├── train.csv Training data
├── test.csv  Test data

## 🔍 Objective

Predict the `Survived` column (1 = survived, 0 = did not survive) using passenger data. The goal is to build a model with good accuracy and generalization.

## 📊 Features Used

- `Pclass` – Ticket class
- `Sex` – Gender
- `Age` – Age in years
- `SibSp` – Number of siblings/spouses aboard
- `Parch` – Number of parents/children aboard
- `Fare` – Ticket fare
- `Embarked` – Port of Embarkation

## 🧠 ML Techniques

The notebook includes:

- Data cleaning and preprocessing
- Handling missing values
- Feature selection and encoding
- Model training ( Random Forest Classifier)
- Evaluation (accuracy, confusion matrix)

## ▶️ How to Run

1. Clone this repository or download the files
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   jupyter notebook "Titanic survival.ipynb"

