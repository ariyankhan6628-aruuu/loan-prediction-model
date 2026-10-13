# 💰 Loan Repayment Prediction Using Machine Learning

## 📌 Project Overview

This project uses Machine Learning to analyze borrower information and predict whether a loan will be repaid. It includes Exploratory Data Analysis (EDA), data preprocessing, model training, and performance evaluation.

## 🎯 Objectives

- Analyze loan and borrower-related data.
- Identify patterns associated with loan repayment.
- Apply different Machine Learning classification algorithms.
- Compare model performance using evaluation metrics.
- Identify a suitable model for predicting loan repayment.

## 🛠️ Technologies Used

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 📊 Dataset Features

The project uses borrower and loan-related information, including:

- Gender
- Marital Status
- Education Level
- Employment Status
- Annual Income
- Debt-to-Income Ratio
- Credit Score
- Loan Amount
- Interest Rate
- Loan Purpose
- Grade and Subgrade

**Target Variable:** `loan_paid_back`

## 🔍 Project Workflow

1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Missing-value and duplicate checks
4. Data preprocessing and feature encoding
5. Numerical feature scaling
6. Training and testing data splitting
7. Machine Learning model training
8. Model evaluation and comparison
9. Visualization of model performance

## 🤖 Machine Learning Models

The following classification algorithms are implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Linear Support Vector Machine (SVM)

## 📈 Model Performance

The following results are recorded in the notebook:

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 86.14% | 93.83% | 88.47% | 91.07% |
| Decision Tree | 86.17% | 94.10% | 88.22% | 91.06% |
| Random Forest | 90.09% | 90.23% | 98.23% | 94.06% |
| Linear SVM | 86.64% | 93.63% | 89.35% | 91.44% |

**Best-performing model in the recorded results:** Random Forest, with 90.09% accuracy and a 94.06% F1 score.

*Note: These scores reflect the notebook's recorded results and may vary when the notebook is rerun.*

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd <YOUR_REPOSITORY_FOLDER>
```

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Prepare the dataset

Place the dataset file named `train.csv` in the project directory. Update the notebook's dataset path if necessary:

```python
import pandas as pd

train = pd.read_csv("train.csv")
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open `loan.ipynb` and execute the cells in sequence.

## 📁 Repository Structure

```text
Loan-Repayment-Prediction/
│
├── loan.ipynb
├── train.csv
└── README.md
```

## 🚀 Future Improvements

- Hyperparameter tuning and cross-validation
- Feature importance and model explainability
- Improved data visualization
- A simple web application for loan repayment predictions
- Fairness and bias evaluation across borrower groups

## ⚠️ Disclaimer

This project is intended for educational and experimental purposes only. Its predictions should not be used as the sole basis for real-world lending decisions.

## 👨‍💻 Author

**Ariyan Khan**

B.Tech Computer Science Engineering Student

Interested in Machine Learning, Artificial Intelligence, and Data Science.
