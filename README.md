# Loan Approval Prediction 

## Overview
This project predicts whether a loan will be approved or not using
Machine Learning techniques.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Flask


### Step 1: Dataset
Used a loan dataset containing applicant details such as income,
education, loan amount, and credit history.

### Step 2: Data Preprocessing
- Removed unnecessary columns like ZIP_Code
- Handled missing values
- Converted categorical values into numerical form
- Scaled the data

### Step 3: Model Training
Trained multiple ML models:
- Logistic Regression
- Decision Tree
- KNN
- Random Forest

### Step 4: Model Evaluation
Compared models using accuracy and classification report
and selected the best model.

### Step 5: Flask Web Application
Created a Flask app to take user input and predict loan approval.

### Step 6: Run the Project
1. Install libraries  
   pip install -r requirements.txt
2. Run app  
   python app.py
3. Open browser  
   http://127.0.0.1:5000/
