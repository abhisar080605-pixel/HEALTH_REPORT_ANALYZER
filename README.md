# HEALTH_REPORT_ANALYZER

A Python-based health report analysis project that combines RULE BASED AI and BASIC MACHINE LEARNING to analyze health parameters to calculate health risk, generate warnings, and suggest action steps.

This project takes common health report values such as BMI, BLOOD SUGAR, BLOOD PRESSURE, HAEMOGLOBIN, CHOLESTROL, HDL, LDL, TRIGLYCERIDES, THYROID LEVEL, T3, T4 and provides a simple health assessment.

#Project Objective

The objective of this project is to create a smart health report analyzer that can:

- Analyze multiple health parameters
- Detect abnormal values
- Calculate risk score
- Generate warnings based on report
- Suggest action steps for the user
- Predict health risk using a basic Machine Learning model
  
# Technologies Used

- pandas
- scikit learn
  decisiontreeclassifier
  
## AI and ML Concepts Used

# Rule-Based AI

This project uses RULE BASED LOGIC to:

 - Analyze health values using medical ranges
 - Generate warnings
 - Suggest action steps

# Machine Learning

This project also uses a DECISION TREE CLASSIFIER to predict health risk based on user input values.

# Features

- BMI Calculation
- Blood Sugar Analysis
- Blood Pressure Analysis
- Haemoglobin Analysis
- Cholesterol Analysis
- Total Cholesterol
- HDL
- LDL
- Triglycerides
- Thyroid Analysis
- Thyroid Level
- T3
- T4
- Risk Score Calculation
- Warning Generation
- Action Steps Recommendation
- ML-Based Health Risk Prediction
  
##Input Parameters

The program takes the following inputs from the user:

- Height
- Weight
- Fasting Blood Sugar
- Systolic Blood Pressure
- Diastolic Blood Pressure
- Haemoglobin Level
- Total Cholesterol
- HDL
- LDL
- Triglycerides
- Thyroid Level
- T3
- T4
  
##Output Generated

The program provides:

- BMI value
- BMI status
- Sugar level status
- Blood pressure status
- Haemoglobin status
- Cholesterol analysis
- Thyroid status
- Rule-based health risk score
- ML predicted health risk
- Warnings based on combined health conditions
- Recommended action steps
- 
##Project Structure

The code contains the following main sections:

1.Imports
2.Machine Learning model training
3.Rule-based health analysis functions
4.User input section
5.Health result dictionary
Risk calculator
6.arnings generator
7.Action steps generator
8.Final output display

##How the Project Works

###Step 1: User Input

The user enters health values through the terminal.

### Step 2: Rule-Based Analysis

The program analyzes each value using predefined medical ranges.

### Step 3: Health Risk Score

The program calculates a health risk score using rule-based conditions.

###Step 4: Machine Learning Prediction

The Decision Tree model predicts whether the user is at health risk or not.

###Step 5: Warning Generation

The system generates warnings if risky combinations are found.

###Step 6: Action Steps

The system suggests action steps based on the report and risk level.

##Installation Steps

### 1. Install Python

Make sure Python 3 is installed on your system.

To check:

python3 --version
