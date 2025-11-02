# 🌸 Iris Flower Classification — CodeAlpha Internship Task 1

This project is part of the **CodeAlpha Data Science Internship** program.

## 📘 Project Overview
The goal of this project is to classify iris flowers into their respective species — *Setosa*, *Versicolor*, or *Virginica* — based on the given flower measurements (sepal length, sepal width, petal length, and petal width).

## 📂 Dataset
The dataset used is the **Iris Dataset**, which contains 150 samples of iris flowers.  
It was provided by CodeAlpha and can also be found on [Kaggle](https://www.kaggle.com/datasets/saurabh00007/iriscsv).

| Column Name | Description |
|--------------|--------------|
| SepalLengthCm | Sepal length in cm |
| SepalWidthCm | Sepal width in cm |
| PetalLengthCm | Petal length in cm |
| PetalWidthCm | Petal width in cm |
| Species | Type of Iris flower (Setosa, Versicolor, Virginica) |

## ⚙️ Workflow
1. **Data Loading & Cleaning** – Load the dataset, check for missing values, and prepare data for training.  
2. **Exploratory Data Analysis (EDA)** – Visualize distributions, relationships, and correlations using Seaborn and Matplotlib.  
3. **Model Training** – Train multiple models: Logistic Regression, Decision Tree, and Random Forest.  
4. **Model Evaluation** – Compare model accuracy and print classification reports.  
5. **Model Saving** – Save the best-performing model as a `.pkl` file using Joblib.

## 📊 Results
- Achieved **high accuracy (>95%)** on all models.  
- The **Random Forest Classifier** performed the best overall.  
- Visualizations clearly show the separability of the iris species.

## 🧠 Libraries Used
- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Joblib

## 🚀 How to Run
1. Clone this repository.  
2. Open the Jupyter Notebook file: `Iris_Flower_Classification_CodeAlpha.ipynb`.  
3. Run all cells sequentially.  
4. The trained model will be saved as `iris_best_model.pkl`.

## 🏁 Conclusion
This project demonstrates basic data science and machine learning workflow for classification problems.  
It covers data preprocessing, visualization, model training, evaluation, and saving results — fulfilling the **Task 1** requirement for the CodeAlpha internship.

---
👨‍💻 **Developed by:** [Your Name]  
📅 **Internship Domain:** Data Science  
🏢 **Organization:** CodeAlpha  
