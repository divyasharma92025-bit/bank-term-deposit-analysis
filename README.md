# Bank Term Deposit Analysis

## 📌 Project Overview

This project analyzes customer data to understand the factors that
influence whether a customer subscribes to a bank term deposit.

The analysis combines **Exploratory Data Analysis (EDA)**, data
visualization, correlation analysis, and a **Logistic Regression** model
to identify important patterns and predictors of term-deposit
subscription.

## 🎯 Objectives

-   Understand customer demographics and characteristics.
-   Analyze customer job and age distributions.
-   Explore the relationship between economic indicators and deposit
    subscription.
-   Analyze campaign and contact-method effectiveness.
-   Identify correlations between numerical variables.
-   Build a Logistic Regression model to predict term-deposit
    subscription.
-   Identify the most influential features used by the model.

## 🗂️ Dataset

The project uses a bank marketing dataset stored in `data.csv`.

The target variable is:

-   `y` --- whether the customer subscribed to a term deposit (`yes` /
    `no`).

The dataset contains customer demographic, financial, campaign, and
economic-related attributes.

## 🛠️ Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Scikit-learn
-   Jupyter Notebook

## 🔍 Analysis Performed

### 1. Customer Demographics

-   Customer age distribution
-   Job-category distribution

### 2. Deposit & Economic Trends

-   Comparison of the average `euribor3m` value by subscription outcome.

### 3. Campaign Effectiveness

-   Analysis of contact methods.
-   Comparison of campaign contact frequency with subscription outcomes.

### 4. Correlation Analysis

A correlation heatmap is used to examine relationships among numerical
features.

### 5. Predictive Modeling

A **Logistic Regression** classifier is trained after:

1.  Converting the target variable from `yes/no` to `1/0`.
2.  One-hot encoding categorical variables.
3.  Splitting the data into training and testing sets using an 80/20
    split.
4.  Training the Logistic Regression model.
5.  Evaluating predictions using accuracy and a classification report.

### 6. Feature Importance

The model coefficients are analyzed to identify the top features
influencing the prediction.

## 📊 Key Insights

The analysis explores several important patterns:

-   Customer age and job category vary across the dataset and can help
    understand the customer base.
-   Economic indicators such as `euribor3m` show differences across
    subscription outcomes.
-   Contact method is analyzed to understand campaign reach.
-   The number of campaign contacts is compared with the final
    subscription outcome.
-   Logistic Regression provides a way to identify features that have
    stronger positive or negative influence on the prediction.

> **Note:** The exact model performance can vary depending on the
> dataset and train/test split.

## 📁 Project Structure

``` text
bank-term-deposit-analysis/
│
├── Advance_Bank_Term_Deposit.ipynb
├── data.csv
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

``` bash
git clone <your-repository-url>
cd bank-term-deposit-analysis
```

### 2. Install dependencies

``` bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Open the notebook

``` bash
jupyter notebook Advance_Bank_Term_Deposit.ipynb
```

Run the notebook cells from top to bottom.

## 📚 Dataset Source

The dataset used for this project was obtained from **Kaggle**.

Please refer to the original Kaggle dataset page for its licensing and
usage terms.

## 🚀 Future Improvements

-   Compare Logistic Regression with Random Forest and other
    classification models.
-   Add precision, recall, F1-score, and ROC-AUC visualizations.
-   Perform feature scaling and hyperparameter tuning where appropriate.
-   Add a confusion matrix.
-   Build an interactive dashboard using Power BI or Streamlit.

## 👩‍💻 Author

**Divya Sharma**

This project was created as part of my learning and practice in
**Python, Data Analytics, and Machine Learning**.
