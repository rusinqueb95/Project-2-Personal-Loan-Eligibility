# Personal Loan Eligibility Prediction
## Project Overview
### This project focuses on predicting personal loan eligibility using machine learning techniques. The goal was to develop an algorithm that evaluates whether individuals would be approved or rejected for personal loans based on key financial and demographic factors such as credit score, education level, annual income, asset values, and number of dependents. This model is designed to assist financial institutions in making more accurate loan approval decisions, reducing risk and improving customer experience.
## Problem Statement
### Financial institutions face significant challenges in evaluating loan eligibility. The goal of this project is to use machine learning to predict whether a loan applicant will be approved or rejected based on their financial profile. We aim to create a model that provides reliable predictions to assist with credit risk assessment.
## Key Attributes
- Credit Score
- Education Level
- Annual Income
- Asset Values
- Number of Dependents
- Loan Approval Status (approved or rejected)
## Project Goals
### To ensure our group remained on track, internal milestones and due dates were established. These milestones provide a clear timeline for completing different stages of the project:
- Project Ideation: Develop project concepts and objectives.
- Data Fetching: Locate and acquire a suitable dataset.
- Data Exploration: Perform exploratory data analysis (EDA) to understand the dataset.
- Data Transformation: Clean the dataset, handle missing values, scale numerical features, and prepare the data for modeling.
- Data Analysis: Use statistical techniques and visualizations to identify key patterns in the data.
- Testing: Train machine learning models, evaluate their performance, and optimize their parameters.
- Creating Documentation: Draft project documentation and create visual assets for presentation.
- Creating the Presentation: Compile findings, models, and results into a presentation format to communicate insights effectively.
### By adhering to these milestones, we ensured timely project completion and maintained accountability within the group.
## Dataset
### We utilized the Loan Approval Prediction Dataset from Kaggle, which includes over 1,000 records of personal loan applicants, providing data such as credit scores, education level, annual income, and loan approval status.
## Tools and Technologies
- Pandas: For data manipulation and preprocessing.
- Scikit-learn: For model development, training, and evaluation.
- Matplotlib & Seaborn: For data visualization and exploration.
- Python: For scripting and implementing the machine learning pipeline.
## Methodology
1. Data Collection
   - We sourced our dataset from Kaggle, containing over 1,000 records of personal loan applicants, including attributes such as credit scores, education level, annual income, and loan approval status.
2. Data Preprocessing
- We imported the necessary libraries to handle and manipulate the dataset
- We read the dataset into a Pandas Dataframe
- Cleaned the data by checking for missing values and duplicates
- Feature Scaling: Scaled the numerical features to ensure unifority in model training
3. Exploratory Data Analysis
  - Visualized relationships between key features and loan approval status using Seaborn and Matplotlib:
4. Data splitting
- Split the dataset into training and testing sets to ensure proper model evaluation
5. Model Development
  - Implemented multiple machine learning models using Scikit-learn, including:
  - Logistic Regression
  - Random Forest Classifier
  ![rfc1](https://github.com/user-attachments/assets/965626c7-7f31-4647-87f0-248e680d717f)
  ![rfc2](https://github.com/user-attachments/assets/af5a0298-963e-4595-8f3f-23c6b3fbeb5b)

  - Support Vector Machine
  ![svm model](https://github.com/user-attachments/assets/d36394af-943e-4769-9469-eabeff4a7385)

  - Decision Tree Classifier
  ![dct1](https://github.com/user-attachments/assets/f8ce634c-76aa-4bb1-9b81-03d79c0f0d21)

6. Model Evaluation
- Evaluated model performance using accuracy, precision, recall, F1-score, and confusion matrix
7. Results
  - Our best-performing model, Random Forest Classifier, achieved an accuracy of X% on the test data.
  - The confusion matrix showed the model’s effectiveness at correctly predicting approved and rejected loans, with strong precision and recall scores for both classes.
