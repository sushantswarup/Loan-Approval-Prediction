# Loan-Approval-Prediction
This project focuses on predicting the likelihood of loan approval for individuals or organizations based on a dataset containing various financial and personal features. The primary objective is to develop and compare different machine learning models to identify the best performing one for loan approval prediction.

## Dataset

The Loan Approval dataset is a collection of financial records and associated information. The features include:
- Cibil score
- Income
- Employment status
- Loan term
- Loan amount
- Assets value
- Loan status (target variable)

## Project Structure
   loan_approval_data.csv       # Dataset file

   Exploratory data analysis
   Data cleaning and feature engineering
   Model selection and comparison
   Model_Evaluation
   README.md                        
   requirements.txt - Required libraries and dependencies

## Getting Started

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/LoanApproval.git
   cd LoanApproval
   ```

2. Set up a virtual environment (optional but recommended):
   ```
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Data Exploration and Preprocessing

An in-depth analysis of the dataset including visualizations and statistical summaries to understand the distribution of features and their relationships. Preprocessingcovers data cleaning, handling missing values, and feature engineering.

## Model Selection and Evaluation

Model Selection focuses on selecting and training various machine learning models, including Naive Bayes, Decision Tree, RandomForest, XGBoost, and Adaboost. It uses techniques like cross-validation to assess each model's performance.

Model Evaluation goes further by evaluating the selected models with more comprehensive metrics and visualizations. It aims to identify the best-performing model for loan approval prediction.

## Results and Conclusion

Based on the experiments conducted, the Histgradientboost achieved the highest accuracy and precision for loan approval prediction. The project demonstrates the importance of data exploration, preprocessing, and careful model selection to achieve meaningful results.

