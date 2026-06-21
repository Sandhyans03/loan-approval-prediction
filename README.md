# Loan Approval Prediction

This project predicts whether a loan application will be approved or not, based on the applicant's personal and financial details. I built this during my Data Science internship at Internship Studio.

# What it does

Banks get a lot of loan applications and need a quick way to estimate whether an applicant is likely to be approved, based on patterns from past data. This model takes details like gender, marital status, education, income, and property area, and predicts the loan status.

# How it works

1. Loaded the loan dataset using Pandas
2. Filled missing values using forward-fill and backward-fill
3. Converted categorical columns (Gender, Married, Education, Self_Employed, Property_Area, Loan_Status) into numerical dummy variables
4. Dropped redundant dummy columns to avoid multicollinearity
5. Split the data into training and test sets
6. Scaled the features using StandardScaler
7. Trained a Logistic Regression model
8. Evaluated the model using accuracy score and a confusion matrix

# Tech used

- Python
- Pandas
- Scikit-learn (Logistic Regression, train_test_split, StandardScaler)

# Files

- `Part2.ipynb` — the main notebook with all the data cleaning, preprocessing, and model training code
- `loan_data_set_lyst1728376986423.csv` — the dataset used

# Running it

Open `Part2.ipynb` in Jupyter Notebook and run all the cells. Make sure the CSV file path matches where you've saved the dataset.
