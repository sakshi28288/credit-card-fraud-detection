# Credit Card Fraud Detection

## Project Description
This project aims to detect fraudulent credit card transactions using a machine learning classification model. The dataset used is the [Credit Card Fraud Detection dataset from Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). The model is trained using Logistic Regression after handling class imbalance by undersampling.

## Dataset
- File: `creditcard.csv`  
- Source: Kaggle  
- Contains anonymized credit card transactions labeled as fraudulent (1) or normal (0).

## How to Run
1. Open the Google Colab notebook fraud_detection.ipynb in this repository.

2. Ensure the dataset file creditcard.csv is uploaded or accessible in Colab.

3. Run the notebook cells step-by-step to execute the project.

## Results
The Logistic Regression model achieved the following performance on the test set:

| Class       | Precision | Recall | F1-Score | Support |
|-------------|-----------|--------|----------|---------|
| Normal (0)  | 0.92      | 0.97   | 0.94     | 147     |
| Fraud (1)   | 0.97      | 0.91   | 0.94     | 149     |

- **Overall Accuracy:** 94%  
- The model shows good precision and recall for both normal and fraudulent transactions.

## Tools and Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
