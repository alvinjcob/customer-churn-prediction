# Customer Churn Prediction

A machine learning project that predicts whether a customer is likely to leave a company (churn) based on customer demographics, account information, and service usage patterns.

##  Overview

Customer churn prediction helps businesses identify customers who are at risk of leaving so that they can take proactive measures to improve customer retention. This project uses supervised machine learning techniques to classify customers as churn or non-churn.

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and evaluation
- Performance comparison using multiple metrics
- Customer churn prediction

##  Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

##  Dataset

Dataset: Customer Churn Dataset

The dataset contains customer information such as:
- Gender
- Senior Citizen
- Tenure
- Monthly Charges
- Total Charges
- Contract Type
- Internet Service
- Payment Method
- Churn (Target Variable)

##  Machine Learning Workflow

1. Import dataset
2. Data cleaning
3. Handle missing values
4. Encode categorical variables
5. Feature scaling
6. Split data into training and testing sets
7. Train machine learning model
8. Evaluate model performance
9. Predict customer churn

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

##  How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

2. Install the required libraries

```bash
pip install -r requirements.txt
```

3. Open the notebook

```
Customer_Churn_Prediction.ipynb
```

4. Run all cells.

## Project Structure

```
customer-churn-prediction/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
├── requirements.txt
└── churn.csv
```
##  Models Implemented

This project compares the performance of two supervised machine learning algorithms:

- Logistic Regression
- Random Forest Classifier

Both models were trained and evaluated using multiple classification metrics to determine their effectiveness in predicting customer churn.

## Model Performance

| Model | Accuracy | Precision | Recall | ROC-AUC |
|------|---------:|----------:|-------:|--------:|
| Logistic Regression | 60% | 39% | **77%** | **0.71** |
| Random Forest | **72%** | **49%** | 30% | 0.69 |

## Key Findings

- Random Forest achieved the highest overall accuracy.
- Logistic Regression achieved significantly higher recall, making it better at identifying customers likely to churn.
- The project demonstrates how different evaluation metrics influence model selection depending on business objectives.

## Results

The model successfully predicts customer churn based on historical customer data. Performance is evaluated using classification metrics such as Accuracy, Precision, Recall, and F1 Score.


