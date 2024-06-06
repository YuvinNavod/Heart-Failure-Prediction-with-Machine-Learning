# Heart Failure Prediction with Machine Learning

This repository contains a project for predicting patient survival in cases of heart failure using machine learning algorithms. The dataset includes various health-related attributes and a binary label indicating survival (0) or death (1) during the follow-up period.

## Dataset Fields
- **age**: Age of the patient (years)
- **anaemia**: Decrease of red blood cells or hemoglobin (boolean)
- **creatinine phosphokinase (CPK)**: Level of the CPK enzyme in the blood (mcg/L)
- **diabetes**: If the patient has diabetes (boolean)
- **ejection fraction**: Percentage of blood leaving the heart at each contraction (percentage)
- **high blood pressure**: If the patient has hypertension (boolean)
- **platelets**: Platelets in the blood (kiloplatelets/mL)
- **sex**: Woman or man (binary)
- **serum creatinine**: Level of serum creatinine in the blood (mg/dL)
- **serum sodium**: Level of serum sodium in the blood (mEq/L)
- **smoking**: If the patient smokes or not (boolean)
- **time**: Follow-up period (days)
- **DEATH_EVENT**: If the patient died during the follow-up period (boolean)

## Project Steps

1. **Data Exploration**
   - Download and load the dataset.
   - Perform basic exploratory data analysis (EDA) to understand the features and the distribution of the target variable (DEATH_EVENT).

2. **Data Preprocessing**
   - Handle missing values (if any).
   - Encode categorical variables (if present).
   - Split the dataset into features (independent variables) and the target variable (DEATH_EVENT).
   - Split the dataset into training and testing sets.

3. **Model Building**
   - Choose classification algorithms: Logistic Regression and Decision Tree.
   - Train the models on the training data.

4. **Model Evaluation**
   - Evaluate the model's performance on the testing data using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.
   - Interpret the model's performance and discuss any insights gained.

## Requirements

- Python 3.x
- pandas
- scikit-learn

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/YuvinNavod/heart-failure-prediction-with-Machine-Learning.git
   cd heart-failure-prediction
