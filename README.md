# employee-attrition-prediction
Employee Attrition Prediction using Machine Learning with EDA, Decision Tree, and Random Forest Classification.

# Employee Attrition Prediction Using Machine Learning

## Project Overview

This project focuses on predicting employee attrition using machine learning techniques. The objective is to identify patterns that may influence employees to leave an organization and develop predictive models that can assist HR teams in making data-driven decisions.

The project includes data exploration, visualization, preprocessing, model training, evaluation, and comparison of machine learning algorithms.

---

## Dataset

The dataset contains employee-related information such as:

- Age
- Department
- Job Role
- Monthly Income
- Overtime Status
- Education
- Marital Status
- Years at Company
- Attrition (Target Variable)

The target variable is **Attrition**, which indicates whether an employee stayed with the company or left.

---

## Project Workflow

### 1. Data Understanding
- Loaded and explored the dataset
- Examined dataset structure and statistics
- Checked data types and dataset dimensions

### 2. Exploratory Data Analysis (EDA)
- Employee Attrition Distribution
- Attrition by Overtime
- Attrition by Department
- Attrition by Job Role
- Attrition by Monthly Income
- Attrition by Age

### 3. Data Preparation
- Encoded categorical variables
- Converted target variable into numerical format
- Feature selection
- Train-test split (80% training, 20% testing)

### 4. Model Training
Two machine learning models were trained:

- Decision Tree Classifier
- Random Forest Classifier

### 5. Model Evaluation
Models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

### 6. Model Comparison
The performance of both models was compared to determine the most effective approach for predicting employee attrition.

---

## Results

| Model | Accuracy |
|---------|---------|
| Decision Tree Classifier | 76.53% |
| Random Forest Classifier | 86.73% |

The Random Forest Classifier achieved the highest accuracy and was selected as the best-performing model.

---

## Key Insights

- Most employees remained with the company.
- Employees working overtime showed higher attrition rates.
- Attrition varied across departments and job roles.
- Employees with lower monthly income were more likely to leave.
- Younger employees showed relatively higher attrition patterns.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Structure
