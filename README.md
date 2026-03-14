# Credit Card Fraud Detection (Machine Learning)

This project builds a machine learning model to detect fraudulent credit card transactions using the Kaggle Credit Card Fraud Detection dataset.

The dataset contains more than 284,000 transactions where only a small fraction are fraud cases, making it a highly imbalanced classification problem.

## What I did in this project

- Performed Exploratory Data Analysis (EDA) to understand transaction patterns
- Handled severe class imbalance using SMOTE
- Split the data into training and testing sets
- Applied feature scaling using StandardScaler
- Trained two models:
  - Logistic Regression
  - Random Forest
- Evaluated models using precision, recall, F1-score and confusion matrix

## Model Performance

The Random Forest model performed best with approximately:

- Precision: 0.91
- Recall: 0.82
- F1-score: 0.86

This means the model detects most fraud transactions while keeping false alarms relatively low.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- imbalanced-learn (SMOTE)

## Project Structure
fraud-detection-ml/
│
├── notebooks/
│ └── fraud_detection.ipynb
│
├── requirements.txt
└── README.md

## Dataset

Dataset used: Kaggle Credit Card Fraud Detection Dataset

(Download the dataset and place it in the "data" folder before running the notebook.)
