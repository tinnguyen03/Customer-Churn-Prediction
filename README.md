# Customer Churn Prediction 

##  Project Description

Perform detailed Exploratory Data Analysis (EDA) to uncover insights about customer exit behavior.
Identify key factors that influence customer decisions to exit.
Build and evaluate multiple machine learning models for exit prediction.
Provide recommendations to improve customer retention.

## 📁 Dataset

The dataset contains information on customers of a bank, including:
- **Customer ID**
- **Credit Score**
- **Geography**
- **Gender**
- **Age**
- **Tenure**
- **Balance**
- **Number of Products**
- **Has Credit Card**
- **Is Active Member**
- **Estimated Salary**
- **Exited** (Target variable)
> Note: The `Exited` column indicates whether the customer has left the bank (`1`) or not (`0`).

## 🔍 Exploratory Data Analysis (EDA)

We explored:
- Distribution of variables
- Correlation with churn
- Demographic patterns
- Feature importance
Key findings are available in the notebook:  
`Customer Exited Prediction.ipynb`

## 🧠 Model Building

We trained and evaluated several models including:
- Logistic Regression
- Random Forest
- XGBoost
Evaluation metrics used:
- Accuracy
- Precision, Recall, F1-Score
- ROC-AUC Score
- Confusion Matrix

## 📌 Results

- The best-performing model was **Random Forest Classifier**
Accuracy: ~82%
Precision (Exited class): ~56%
Recall (Exited class): ~69%
F1-Score (Exited class): ~62%

## 🛠️ Technologies Used

-Programming Language: Python
-Libraries:
Data Processing: pandas, numpy
Visualization: matplotlib, seaborn
Modeling: scikit-learn, logistic regression, decision tree, random forest
Evaluation: accuracy_score, classification_report, confusion_matrix

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/tinnguyen03/Customer-Churn-Prediction.git
   cd Customer-Exited-Prediction
