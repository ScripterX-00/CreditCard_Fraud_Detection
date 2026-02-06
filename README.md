## CreditCard_Fraud_Detection
This project focuses on detecting fraudulent credit card transactions using the K-Nearest Neighbors (KNN) machine learning algorithm. The implementation is done entirely in Google Colab, making it easy to run without any local setup.

## Project Overview

Credit card fraud is a major issue in financial systems. The goal of this project is to build a machine learning model that can classify transactions as fraudulent or legitimate based on transaction features.

- Algorithm Used: K-Nearest Neighbors (KNN)
- Platform: Google Colab
- Type: Supervised Binary Classification

## Dataset Description

The dataset contains credit card transaction data

Features are numerical and anonymized for privacy

The target column:

- Class = 0 → Normal transaction
- Class = 1 → Fraudulent transaction

The dataset is highly imbalanced, which is common in fraud detection problems

##  Technologies & Libraries Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

## Workflow

- Import Required Libraries
- Load Dataset
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature scaling (important for KNN)
- Train-test split
- Model Training
- Apply KNN classifier
- Model Evaluation
- Classification Report
- Result Analysis

## Machine Learning Model
K-Nearest Neighbors (KNN)

- KNN is a distance-based algorithm
- It classifies a data point based on the majority class of its nearest neighbors

Feature scaling is crucial for good performance

- Example:

from sklearn.neighbors import KNeighborsClassifier
```bash

knn = KNeighborsClassifier(n_neighbors=5)
knn.fit(X_train, y_train)

```

##  Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Note: Accuracy alone is not enough due to class imbalance. Precision and recall are important in fraud detection.

## How to Run the Project (Google Colab)

- Open Google Colab
- Upload the .ipynb notebook
- Upload the dataset or mount Google Drive
- Run all cells sequentially
- View results and evaluation metrics


##  Project Structure

```
CreditCard_Fraud_Detection/
│
├── CreditCard_Fraud_Detection.ipynb
├── creditcard.csv
└── README.md   # Project documentation
```
---

##  Key Learnings

- Handling imbalanced datasets
- Importance of feature scaling in KNN
- Evaluating classification models beyond accuracy
- Practical implementation of fraud detection systems

## Future Improvements

- Try other algorithms (Logistic Regression, Random Forest, XGBoost)
- Apply SMOTE or undersampling techniques
- Hyperparameter tuning for optimal K value
- Deploy model using Flask or FastAPI

##  Author
Dibyajyoti Jana
