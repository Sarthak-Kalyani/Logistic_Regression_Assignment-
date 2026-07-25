# Titanic Survival Prediction using Logistic Regression

This project implements a **Logistic Regression** model to predict passenger survival on the Titanic dataset. It demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and interpretation of results using Python and Scikit-Learn.

---

## Project Objective

The objective of this project is to build a binary classification model that predicts whether a passenger survived the Titanic disaster based on features such as age, gender, passenger class, fare, and family information.

---

## Dataset

- **Dataset Name:** train_and_test2.csv
- **Rows:** 1309
- **Columns:** 9

### Features

- Passengerid
- Age
- Fare
- Sex
- sibsp
- Parch
- Pclass
- Embarked
- Survived (Target Variable)

---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset inspection
- Missing value analysis
- Duplicate value check
- Class distribution
- Correlation heatmap
- Histograms
- Boxplots
- Pairplot
- Outlier analysis

---

## Data Preprocessing

- Renamed target column
- Handled missing values
- Removed unnecessary feature (Passengerid)
- Feature Scaling using StandardScaler
- Train-Test Split (80:20)

---

## Machine Learning Model

**Algorithm Used**

- Logistic Regression

Model Parameters:

- Random State: 42
- Train-Test Split: 80:20

---

## Model Performance

| Metric | Score |
|---------|------:|
| Accuracy | 76.72% |
| Precision | 64.29% |
| Recall | 36.99% |
| F1-Score | 46.96% |

---

## Key Insights

- Gender is the most important feature affecting survival.
- Passenger Class has a significant impact on survival.
- Fare contributes positively to prediction.
- Age has a comparatively smaller influence.
- Logistic Regression provides a simple and interpretable binary classification model.

---

## Repository Structure

```
Logistic_Regression_Assignment/
│
├── Logistic_Regression_Assignment.ipynb
├── train_and_test2.csv
├── Logistic_Regression_Report.pdf
├── README.md
└── requirements.txt
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/Sarthak-Kalyani/Logistic_Regression_Assignment-.git
```

2. Open the project folder

```bash
cd Logistic_Regression_Assignment-
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook and run all cells.

---

## Learning Outcomes

This project helped in understanding:

- Binary Classification
- Logistic Regression
- Data Cleaning
- Exploratory Data Analysis
- Feature Scaling
- Model Evaluation
- Confusion Matrix
- Classification Report
- Machine Learning Workflow

---

##  Author

**Sarthak Kalyani**

GitHub: https://github.com/Sarthak-Kalyani

---

⭐ If you found this project useful, consider giving it a star!
