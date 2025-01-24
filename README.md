#  UCI Bank Marketing Prediction Project

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Status](https://img.shields.io/badge/Status-Completed-green)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-orange)

##  Project Overview

This project leverages the [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing) to predict whether a customer will subscribe to a term deposit. Using machine learning algorithms like **KNN**, **Naïve Bayes**, **Decision Trees**, and more, the project demonstrates data preprocessing, model building, and performance evaluation.

---

##  Features

1. **Data Processing:**
   - Cleaning missing values.
   - Encoding categorical variables and normalizing features.

2. **Exploratory Data Analysis (EDA):**
   - Visualizing distributions and feature relationships.
   - Identifying important predictors.

3. **Machine Learning Models:**
   - Implementation of multiple algorithms:
     - KNN
     - Naïve Bayes
     - Decision Trees
     - Random Forests
     - Logistic Regression
   - Model evaluation using metrics (accuracy, precision, recall, F1-score).

4. **Visualization:**
   - Confusion matrix and ROC curves for model comparison.

---

##  Project Structure

/UCI-Bank-Marketing-Prediction/ ├── data/ # Dataset files ├── notebooks/ # Jupyter Notebooks for EDA and experiments ├── src/ # Python scripts for data processing and modeling ├── models/ # Trained models and saved files ├── results/ # Performance reports and visualizations ├── requirements.txt # Python dependencies ├── README.md # Project documentation ├── LICENSE # Project license ├── .gitignore # Ignored files and directories

---

##  Dataset Preview

The dataset consists of 41,188 records and 21 columns, including client demographic, financial details, and campaign-related information. Below is a preview:

| Age | Job          | Marital  | Education | Default | Balance | Housing | Loan | Contact | Day | Month | Duration | Campaign | PDays | Previous | POutcome | Subscription |
|-----|--------------|----------|-----------|---------|---------|---------|------|---------|-----|-------|----------|----------|-------|----------|----------|--------------|
| 58  | Management   | Married  | Tertiary  | No      | 2143    | Yes     | No   | Unknown | 5   | May   | 261      | 1        | -1    | 0        | Unknown  | No           |
| 44  | Technician   | Single   | Secondary | No      | 29      | Yes     | No   | Unknown | 5   | May   | 151      | 1        | -1    | 0        | Unknown  | No           |
| 33  | Entrepreneur | Married  | Secondary | No      | 2       | Yes     | Yes  | Unknown | 5   | May   | 76       | 1        | -1    | 0        | Unknown  | No           |
| 47  | Blue-Collar  | Married  | Unknown   | No      | 1506    | Yes     | No   | Unknown | 5   | May   | 92       | 1        | -1    | 0        | Unknown  | No           |
| 33  | Unknown      | Single   | Unknown   | No      | 1       | No      | No   | Unknown | 5   | May   | 198      | 1        | -1    | 0        | Unknown  | No           |

**Target Variable:**
- `y`: Indicates whether the client subscribed to a term deposit (`yes` or `no`).



---

##  Setup and Usage

### Prerequisites
- **Python 3.8+**
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### Installation Steps
#### 1. Clone the repository:
```
   git clone https://github.com/blueberrygurl/UCI-Bank-Marketing-Prediction.git
   cd UCI-Bank-Marketing-Prediction
```

#### 2. Install dependencies:
```
  pip install -r requirements.txt
```
#### 3. Open the Jupyter Notebook for exploration:
```
  jupyter notebook
```


## 💌 Contact
For questions or suggestions, contact me at: mohhiaya3@gmail.com.
