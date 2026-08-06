# Loan-prediction
# 🏦 Loan Prediction using Machine Learning

A beginner-friendly Machine Learning project that predicts whether a loan application will be **Approved** or **Rejected** based on applicant information. This project covers the complete data analysis workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation using Logistic Regression.

---

## 📌 Project Overview

The objective of this project is to build a classification model that predicts loan approval status using applicant details such as income, education, employment status, credit history, and loan amount.

This project demonstrates the complete Machine Learning pipeline:

- Data Loading
- Data Cleaning
- Handling Missing Values
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Encoding
- Model Training
- Model Evaluation

---

## 📂 Dataset

The dataset contains information about loan applicants, including:

- Gender
- Married
- Dependents
- Education
- Self Employed
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area
- Loan Status (Target Variable)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Data Preprocessing

The following preprocessing steps were performed:

- Checked missing values
- Filled missing categorical values using:
  - Forward Fill
  - Mode
  - Backward Fill
- Filled numerical missing values using:
  - Median
- Verified data types
- Prepared clean dataset for analysis

---

## 📈 Exploratory Data Analysis (EDA)

EDA was performed to better understand the data through visualizations such as:

- Loan Amount Distribution
- Income Distribution
- Feature Relationships
- Data Patterns

Libraries used:

- Matplotlib
- Seaborn

---

## ⚙️ Feature Engineering

Additional preprocessing included:

- Creating categorical bins
- One-Hot Encoding using `pd.get_dummies()`
- Preparing features for machine learning

---

## 🤖 Machine Learning Model

### Algorithm Used

- Logistic Regression

### Train-Test Split

- Training Data
- Testing Data

The model was trained using Scikit-learn's Logistic Regression classifier.

---

## 📊 Model Evaluation

The model performance was evaluated using:

- Accuracy Score
- Precision Score
- Recall Score

These metrics help measure how well the classifier predicts loan approval.

---

## 📁 Project Structure

```
Loan-Prediction/
│
├── loanpredictiontask.ipynb
├── loanprediction.csv
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Loan-Prediction.git
```

2. Open the project folder

3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open Jupyter Notebook

```bash
jupyter notebook
```

5. Run all notebook cells.

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data Cleaning Techniques
- Handling Missing Values
- Exploratory Data Analysis
- Feature Engineering
- Data Encoding
- Logistic Regression
- Model Evaluation
- Building an End-to-End Machine Learning Workflow
---
## 🎯 Future Improvements
- Compare multiple machine learning models
- Perform Hyperparameter Tuning
- Feature Selection
- Cross Validation
- Deploy the model using Streamlit or Flask

---
## 👩‍💻 Author

**Eman Haroon**

BS Data Science Student

Interested in:
- Machine Learning
- Data Analytics
- Python Development
- Artificial Intelligence

---

⭐ If you found this project helpful, consider giving it a star!
