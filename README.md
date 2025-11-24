# 🫀 **Heart Disease Prediction using Machine Learning (Logistic Regression)**

This project predicts the risk of heart disease using a Logistic Regression model. The dataset includes common clinical features used to identify whether a person is likely to develop coronary heart disease (CHD) within 10 years.
This project was implemented in a Jupyter Notebook with basic exploratory data analysis and model evaluation.

## 📌 **Project Overview**

The goal of this project is to build a simple machine learning model that can classify whether a patient is at risk of heart disease based on several health parameters.

## **Steps performed in the notebook:**

- Imported necessary libraries (NumPy, Pandas, Seaborn, Matplotlib, scikit-learn)

- Loaded and cleaned the dataset (removed missing values)

- Performed basic exploratory data analysis (count plots, distribution visualization)

- Split the data into training and testing sets

- Trained a Logistic Regression model

- Evaluated the model using:

- Accuracy Score

- Confusion Matrix

- Visualization using Seaborn heatmap

## 🗂️ **Dataset**

The dataset used contains attributes like:

- Age

- Sex

- Resting blood pressure

- Cholesterol

- Glucose

- Smoking

- Diabetes

- Heart rate

- Blood pressure levels

- TenYearCHD (target variable — 1 indicates heart disease risk)

## 🚀 **How to Run**
### 1️⃣ **Clone the repository**
```
git clone https://github.com/Indhu-Vempatapu/HeartDiseasePrediction.git
```
### 2️⃣ **Install required libraries**
```
pip install numpy pandas seaborn matplotlib scikit-learn
```
### 3️⃣ **Open the notebook**
jupyter notebook prediction.ipynb

## 📊 **Model Used**

- Logistic Regression (Binary Classification)

Chosen because it is simple, fast, and widely used for medical predictions.

## 🧪 **Model Evaluation**

- Accuracy Score printed in the notebook

- Confusion Matrix visualized using seaborn.heatmap()

These metrics help understand how well the model detects both positive and negative cases of heart disease.

## 📈 **Visualizations Included**

- Count plot of CHD cases

- Histogram / distribution visualization

- Confusion matrix heatmap

## 🛠️ **Tech Stack**

- Python

- NumPy

- Pandas

- Matplotlib

- Seaborn

- Scikit-learn

- Jupyter Notebook
