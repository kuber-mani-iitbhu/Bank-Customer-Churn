# Bank Customer Churn Prediction — Machine Learning & Deep Learning

An end-to-end **Binary Classification** project to predict whether a bank customer is likely to leave the bank using Exploratory Data Analysis (EDA), traditional Machine Learning algorithms, XGBoost, and Neural Networks.

## 🎯 Objective

The objective is to predict customer churn using the target variable `Exited`.

| Value | Meaning |
|---|---|
| 0 | Customer did not exit |
| 1 | Customer exited |

This is a binary classification problem focused on identifying customers who are likely to discontinue their banking relationship.

## 🛠️ Project Workflow

The project follows an end-to-end Machine Learning pipeline:

1. **Data Loading & Understanding** – Load datasets and understand their structure.
2. **Exploratory Data Analysis (EDA)** – Analyze feature distributions, relationships, and patterns.
3. **Data Quality Analysis** – Examine missing values and class imbalance.
4. **Feature & Target Separation** – Separate independent variables and the target variable.
5. **Data Splitting** – Create training, validation, and test datasets.
6. **Preprocessing** – Apply categorical encoding and feature scaling.
7. **Machine Learning Models** – Train and compare traditional ML algorithms.
8. **Deep Learning** – Build and evaluate a Neural Network.
9. **XGBoost Optimization** – Tune XGBoost hyperparameters to improve model performance.
10. **Final Evaluation** – Evaluate the selected model on held-out test data.
11. **Kaggle Submission** – Generate customer churn probabilities for the competition submission.

## 🧰 Tech Stack

- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, XGBoost
- **Deep Learning:** Neural Networks
- **Environment:** Kaggle Notebooks, Jupyter Notebook

## 📊 Key Focus Areas

- Exploratory Data Analysis and feature understanding
- Handling class imbalance
- Feature engineering and preprocessing
- Machine Learning vs. Deep Learning model comparison
- Hyperparameter tuning
- Binary classification and churn probability prediction

## 📁 Dataset

Dataset: [Kaggle Playground Series – Season 4, Episode 1](https://www.kaggle.com/competitions/playground-series-s4e1)

The competition provides:
- `train.csv` – Training dataset
- `test.csv` – Test dataset
- `sample_submission.csv` – Sample submission format

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/kuber-mani-iitbhu/Bank-Customer-Churn.git
cd Bank-Customer-Churn
```

Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

Open the notebook using Jupyter or VS Code.

## 👨‍💻 Author

**Kuber Mani**

[GitHub](https://github.com/kuber-mani-iitbhu)

---

*This project is part of my hands-on learning journey in Machine Learning, Deep Learning, and Data Science.*
