# **Credit Card Debt Prediction**

This repository demonstrates a predictive model for **credit card debt (Balance)** using customer attributes from the `credit.csv` dataset. The project includes **Exploratory Data Analysis (EDA)**, building a **linear regression model**, evaluating model diagnostics, and suggesting potential improvements.

---

## **File Formats**

To enhance user-friendliness, the project files are available in two formats:
1. **Jupyter Notebook (.ipynb)**
2. **HTML format** (easily viewable without a Jupyter environment)

---

## **Steps Overview**

### 1. **Problem Definition**
   - Define the objective of predicting credit card debt based on customer attributes.

### 2. **Load the Dataset**
   - Import and preview the `credit.csv` dataset.

### 3. **Inspect Dataset Structure and Missing Values**
   - Analyze dataset structure and address any missing values.

### 4. **Convert Categorical Variables to Dummy Variables**
   - Transform categorical variables into numerical dummy variables for analysis.

### 5. **Exploratory Data Analysis (EDA)**
   - Perform descriptive statistics and visualizations to understand data patterns.

### 6. **Define Predictors (X) and Response Variable (y)**
   - Identify independent (predictors) and dependent (response) variables.

### 7. **Split Data into Training and Testing Sets**
   - Divide the dataset for model training and evaluation.

### 8. **Add Constant for Statsmodels Linear Regression**
   - Prepare data for linear regression using `statsmodels`.

### 9. **Plot Histogram and QQ Plot to Check Normality of Residuals**
   - Evaluate residuals' distribution for model assumptions.

### 10. **Perform Shapiro-Wilk Test for Normality**
   - Statistically test the normality of residuals.

---

## **Usage Instructions**

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-debt-prediction.git
   cd credit-card-debt-prediction

2. Open the .ipynb file in Jupyter Notebook
   jupyter notebook credit_card_debt_prediction.ipynb

3. Alternatively, open the .html file in your web browser for a quick view of the notebook content. 
