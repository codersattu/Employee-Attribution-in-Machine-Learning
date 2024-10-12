# Employee Attrition Prediction in Machine Learning
## Problem Statement
Employee attrition, defined as a reduction in the workforce due to resignation or retirement, poses a significant challenge for companies. It leads to financial losses in hiring and training new employees and can negatively affect the company's brand value. A fast-growing company has observed numerous employees leaving over the last three years. Their HR department has always been reactive but now aims to predict employee attrition proactively based on available data. The goal is to predict whether an employee will leave the company using the given dataset.

## Dataset
### Files
Train_Dataset.csv: This dataset is used to train the machine learning model. It contains various features about the employees along with the Attrition target variable, indicating whether an employee left the company or not.

Test_Dataset.csv: This dataset is used to test the model's performance on unseen data. It contains the same features as the training dataset but without the Attrition target variable.

Data_Dictionary.csv: This file contains the description of the variables used in the dataset.

### Features in the Dataset
The dataset contains the following variables:

EmployeeID: Unique identifier for each employee.
Attrition: Target variable indicating whether an employee left the company (1) or not (0) – only present in the training dataset.
Age: Age of the employee.
TravelProfile: Job profile travel status (e.g., 'Rarely', 'Frequently').
Department: Department of the employee (e.g., 'Analytics', 'Sales').
HomeToWork: Distance between the employee's home and workplace (in kilometers).
EducationField: Employee's education background.
Gender: Employee's gender.
HourlnWeek: Average hours worked per week.
Involvement: Employee’s involvement level.
WorkLifeBalance: Employee's self-reported work-life balance score.
JobSatisfaction: Employee's job satisfaction score.
ESOPs: Whether the employee has stock ownership (1 for yes, 0 for no).
NumCompaniesWorked: Number of companies the employee has previously worked at.
OverTime: Whether the employee works overtime or not.
SalaryHikeLastYear: Salary increase percentage in the last year.
WorkExperience: Total years of work experience.
LastPromotion: Years since the employee's last promotion.
CurrentProfile: Number of years in the current job profile.
MaritalStatus: Employee’s marital status.
MonthlyIncome: Employee’s monthly salary.

## Requirements
Python 3.x
Libraries used:
pandas
numpy
scikit-learn
matplotlib (for visualization)
seaborn (for visualization)

## How to Run the Code
Clone this repository.

## Install the required libraries by running:

bash
Copy code
pip install -r requirements.txt
Place the dataset files (Train_Dataset.csv, Test_Dataset.csv, and Data_Dictionary.csv) in the appropriate folder.

Open and run the Jupyter Notebook Employee_Attrition.ipynb to train and test the attrition prediction model.

## Model Overview
The machine learning model uses a combination of classifiers to predict employee attrition based on various features. The model was trained on the Train_Dataset.csv and evaluated using the Test_Dataset.csv. The chosen algorithms include:

## Decision Trees
Random Forest
Gradient Boosting
Voting Classifier (combination of multiple models)
The performance of the model is evaluated using metrics such as accuracy, precision, recall, and F1 score. The model aims to generalize well to unseen data and provide accurate attrition predictions.

## Conclusion
This project builds a predictive model to help HR teams proactively manage employee attrition. By understanding the key factors influencing attrition, the company can take steps to reduce turnover and its associated costs.
