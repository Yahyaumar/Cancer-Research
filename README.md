🧬 Cancer Research Project
This project leverages data science techniques and machine learning models to analyze and predict cancer diagnoses using a publicly available dataset. The analysis includes exploratory data analysis, data preprocessing, visualization, model training, and evaluation to deliver actionable insights into the detection of malignant and benign tumors.

📊 Project Overview
The notebook performs:

Data Cleaning and Preprocessing

Exploratory Data Analysis (EDA)

Feature Engineering

Model Building with machine learning algorithms

Evaluation using accuracy, precision, recall, and confusion matrix

Visualization to support findings

🧠 Machine Learning Models Used
Logistic Regression

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Decision Tree

Random Forest

Each model was evaluated to determine its effectiveness in classifying tumors.

📁 Dataset
The project uses the Breast Cancer Wisconsin (Diagnostic) Dataset available from the UCI Machine Learning Repository.

Features include:

Radius, texture, perimeter, area, smoothness, compactness, concavity, etc.

Diagnosis labels: M for Malignant and B for Benign.

🛠️ Tech Stack
Python (Jupyter Notebook)

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

✅ Results
Achieved high accuracy with Random Forest and SVM classifiers.

Identified most important features contributing to cancer diagnosis.

Visualized class distributions and feature correlations.

💡 Insights
Feature scaling and preprocessing significantly impacted model performance.

Ensemble methods like Random Forest outperformed individual models.

Visual EDA helped in understanding feature importance and dataset balance.

📌 How to Run
Clone the repository

Install required dependencies:
pip install -r requirements.txt

Run the notebook:
jupyter notebook Cancer\ Research.ipynb
