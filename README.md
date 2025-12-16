#### 📖 Project Overview

This project focuses on building a binary classification model to predict whether an individual is eligible for a loan based on their personal, financial, and employment details.
The model uses Logistic Regression, a widely used and interpretable machine learning algorithm for classification problems.

Financial institutions often face challenges in assessing loan applications efficiently and fairly. This project demonstrates how data-driven decision making can help automate and improve the loan approval process.

**🎯 Objective**

The main objective of this project is to:

- Predict loan approval status (Approved / Not Approved)

- Reduce manual evaluation effort

- Improve consistency in loan decision-making

**📊 Dataset Description**

The dataset contains information about loan applicants, including:

- Applicant income

- Co-applicant income

- Loan amount

- Loan amount term

- Credit history

- Employment status

- Marital status

- Education level

- Property area

The target variable is _Loan Status_, which indicates whether the loan was approved or not.

**⚙️ Methodology**

- Data Cleaning

  - Handled missing values

  - Removed inconsistencies

  - Converted categorical variables using encoding techniques

- Exploratory Data Analysis (EDA)

  - Analyzed feature distributions

  - Studied relationships between features and loan approval

- Feature Scaling

  - Applied standardization to numerical features for better model performance

- Model Building

  - Implemented Logistic Regression

  - Trained the model on the training dataset

  - Evaluated performance on the test dataset

- Model Evaluation

  - Accuracy score

  - Confusion matrix

  - Precision, recall, and F1-score

**📈 Results**

The Logistic Regression model successfully classified loan eligibility with satisfactory accuracy.
The model provides interpretable coefficients, helping understand which features most influence loan approval decisions.
