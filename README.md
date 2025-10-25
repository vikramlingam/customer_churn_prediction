# AlphaCom Customer Churn Prediction

This repository contains the end-to-end data science project for analyzing and predicting customer churn at AlphaCom, a telecommunications provider.

## Business Problem
The project's goal is to address rising customer churn, which is impacting revenue. We build a predictive model to identify customers at high risk of leaving and analyze the key factors driving their decisions. This enables AlphaCom to move from a reactive to a proactive retention strategy.

## Repository Structure
- **customer_churn.csv**: The raw, uncleaned dataset used for the analysis.  
- **customer_churn.ipynb**: The complete Python notebook containing all data cleaning, exploratory data analysis (EDA), preprocessing, and modeling.  
- **customer_churn.html**: An HTML export of the fully executed notebook for easy viewing in any browser.  

## Key Findings & Model Performance
**Key Churn Drivers:** The analysis identified tenure (how new a customer is), Contract_Month-to-month, and high MonthlyCharges as the most significant predictors of churn.  
**Final Model:** A Logistic Regression model was selected as the champion model for its superior performance and interpretability.  
**Performance:** The final model achieved a ROC AUC of 0.85 and, most importantly, a Recall of 0.79, successfully identifying 79% of all customers who were truly at risk of churning.

## How to Run
1. Clone this repository.
   ```bash
   git clone https://github.com/<your-username>/customer_churn_prediction.git
   cd customer_churn_prediction

## Installation and Execution

### Install the required libraries
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

## Run the Project

1. Launch **Jupyter Notebook** and open `Customer_Churn.ipynb`.  
2. Run all cells to reproduce the complete analysis.  
3. Alternatively, for a quick, non-interactive review, simply open the `customer_churn.html` file in your web browser.
