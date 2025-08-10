# Diabetes
Machine learning project to predict diabetes in patients.
# Diabetes
Machine Learning Project for a diabetes dataset.

Diabetes Prediction using Logistic Regression and K-Nearest Neighbors
📌 Overview
This project is a machine learning classification task that predicts whether a patient has diabetes based on diagnostic medical measurements.
We use Logistic Regression and K-Nearest Neighbors (KNN) as predictive models to classify patients as diabetic or non-diabetic.

The dataset comes from the National Institute of Diabetes and Digestive and Kidney Diseases and contains medical data for female patients of Pima Indian heritage, aged 21 years or older.

📊 Dataset Description
Source: Pima Indians Diabetes Database
Objective: Predict diabetes diagnosis based on health measurements.
Target Variable: Outcome

1 → Patient has diabetes

0 → Patient does not have diabetes

Features:

Feature	Description
Pregnancies	Number of times pregnant
Glucose	Plasma glucose concentration after 2 hours in an oral glucose tolerance test
BloodPressure	Diastolic blood pressure (mm Hg)
SkinThickness	Triceps skinfold thickness (mm)
Insulin	2-hour serum insulin (mu U/ml)
BMI	Body mass index (weight in kg / (height in m)²)
DiabetesPedigreeFunction	Diabetes pedigree function score
Age	Age in years
Outcome	Class label (0 or 1)

⚙️ Methods Used
Data Preprocessing

Handling missing or zero values

Feature scaling for KNN

Splitting data into training and test sets

Models Implemented

Logistic Regression

Used for its interpretability and effectiveness in binary classification.

K-Nearest Neighbors (KNN)

Used to explore distance-based classification performance.

Evaluation Metrics

Accuracy

Precision, Recall, AUC, and F1-Score

📈 Results
The performance of both Logistic Regression and KNN is compared to determine which model better predicts diabetes in this dataset.
Final Accuracy, Precision, Recall, AUC, and F1-Score reports are displayed after training.
