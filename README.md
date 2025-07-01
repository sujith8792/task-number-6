# task-number-6
# Heart Disease Classification with Decision Trees and Random Forests

## Overview
This project implements machine learning models to classify the presence of heart disease using the Heart Disease dataset. We will utilize two popular algorithms: **Decision Tree Classifier** and **Random Forest Classifier**. The goal is to understand how these models work and evaluate their performance.

## Dataset
The dataset used for this project is the **Heart Disease dataset**. Ensure that the dataset file is named `heart_disease_dataset.csv` and is located in the same directory as the script. The dataset contains various features related to heart health and a target variable indicating the presence of heart disease.

## Tools Used
- **Python**: The programming language used for implementation.
- **Pandas**: A library for data manipulation and analysis.
- **Scikit-learn**: A machine learning library for Python that provides tools for model training and evaluation.
- **Matplotlib**: A plotting library for visualizing the decision tree.

## Steps
1. **Load the Dataset**: The dataset is loaded from the file `heart_disease_dataset.csv`.
2. **Preprocess the Data**: The dataset is split into features (X) and target variable (y).
3. **Train a Decision Tree Classifier**: A decision tree model is trained and visualized.
4. **Train a Random Forest Classifier**: A random forest model is trained and its accuracy is compared with the decision tree.
5. **Evaluate Models**: Both models are evaluated using accuracy and cross-validation to ensure robustness.
6. **Feature Importance**: The importance of each feature in the random forest model is interpreted and displayed.

## Results
- The accuracy of the Decision Tree and Random Forest models is printed to the console.
- A visualization of the decision tree is saved as `decision_tree.png`.
- Feature importances are displayed in the console.

## How to Run
Install the required libraries using:
 
   pip install pandas scikit-learn matplotlib
