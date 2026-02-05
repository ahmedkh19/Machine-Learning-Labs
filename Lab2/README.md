# Lab 2: Heart Disease Classification

## Dataset

The dataset used in this lab is the **Heart Disease** dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease). It contains 297 patient records with 13 medical attributes and 1 target variable.

### Features

| Feature    | Description                                      |
|------------|--------------------------------------------------|
| age        | Age in years                                     |
| sex        | Sex (1 = male, 0 = female)                       |
| cp         | Chest pain type (1-4)                            |
| trestbps   | Resting blood pressure (mm Hg)                   |
| chol       | Serum cholesterol (mg/dl)                        |
| fbs        | Fasting blood sugar > 120 mg/dl (1 = true)       |
| restecg    | Resting electrocardiographic results (0-2)       |
| thalach    | Maximum heart rate achieved                      |
| exang      | Exercise induced angina (1 = yes, 0 = no)        |
| oldpeak    | ST depression induced by exercise                |
| slope      | Slope of the peak exercise ST segment            |
| ca         | Number of major vessels colored by fluoroscopy    |
| thal       | Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect) |

### Target Variable

- `target`: 0 = No heart disease, 1 = Heart disease present

## Machine Learning Problem

This is a **binary classification** problem. Given a patient's medical attributes, the goal is to predict whether the patient has heart disease or not.

The model is expected to learn patterns in the medical features (such as age, cholesterol levels, chest pain type, and heart rate) that distinguish between patients with and without heart disease.

## Methodology

The planned workflow for this project:

1. **Dataset Selection** - Choose the UCI Heart Disease dataset
2. **Data Loading** - Load the CSV file using Pandas
3. **Data Preprocessing** - Handle missing values, encode categorical variables, normalize features
4. **Train/Test Split** - Split data into training (80%) and testing (20%) sets
5. **Model Training** - Train classification models (e.g., Decision Tree, KNN, Random Forest)
6. **Model Evaluation** - Evaluate using accuracy, precision, recall, and confusion matrix
7. **Results** - Compare model performance and select the best model
