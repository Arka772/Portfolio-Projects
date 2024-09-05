# Customer Churn Prediction: Banking Dataset

## Project Overview

This project focuses on predicting customer churn for a bank using machine learning models. The dataset contains customer profiles and behavioral attributes. The objective is to develop a robust model that can help the bank improve its customer retention strategy by identifying customers at risk of leaving.

### Objectives
- Analyze the factors contributing to customer churn.
- Build and evaluate machine learning models to predict churn.
- Provide insights that can help banks reduce churn through targeted interventions.

### Tools & Skills Used
- **Jupyter Notebook (Python)**: Data Analysis, Model Building
- **Libraries**: pandas, numpy, scikit-learn, matplotlib
- **Presentation**: PowerPoint (for summarizing results)
- **Skills**: Exploratory Data Analysis, Feature Selection, Machine Learning, Model Evaluation

### Dataset

The dataset includes customer profiles from a bank with the following key fields:
- **CustomerId**: Unique identifier for each customer
- **CreditScore**: Numerical value representing the customer's credit score
- **Geography**: Customer's country (France, Spain, Germany)
- **Gender**: Customer's gender (Male, Female)
- **Age**: Customer's age
- **Tenure**: Number of years the customer has been with the bank
- **Balance**: Customer's account balance
- **NumOfProducts**: Number of products the customer uses
- **IsActiveMember**: Whether the customer is an active member (1 = yes, 0 = no)
- **Exited**: Whether the customer has churned (1 = yes, 0 = no)

- **Files**: `Bank_Churn.csv` and `Bank_Churn_Data_Dictionary.csv`

### Key Steps

1. **Exploratory Data Analysis (EDA)**:
   - Analyzed the distribution of variables such as Age, Balance, and NumOfProducts.
   - Checked for missing values and outliers.
   - Performed statistical tests like ANOVA and Chi-square to select significant features.

2. **Feature Selection**:
   - Final features used for modeling include NumOfProducts, IsActiveMember, Age, and Balance.

3. **Model Development**:
   - **Logistic Regression**: Baseline model with 77% accuracy.
   - **Decision Tree Classifier**: Achieved an accuracy of 79%.
   - **Random Forest Classifier**: Final model with an accuracy of 82%.

4. **Model Evaluation**:
   - Metrics like Accuracy, Precision, Recall, F1-Score, and ROC AUC were used to evaluate the models.
   - The final model was a Random Forest classifier with 82% accuracy.

### Final Results

- **Best Model**: Random Forest Classifier
- **Key Metrics**:
  - **Accuracy**: 82%
  - **Precision**: 0.85 (Class 0), 0.73 (Class 1)
  - **Recall**: 0.86 (Class 0), 0.69 (Class 1)
  - **F1-Score**: 0.85 (Class 0), 0.71 (Class 1)

### Full Report

For detailed insights and visualizations, refer to the full report here: [Customer Churn Prediction Report (PPT)](./Report_Arka_6075.ppt.pptx).

You can also explore the Jupyter Notebook code used to develop the model: [Customer Churn Prediction Code (Jupyter)](./Code_Arka_6075.ipynb.ipynb).

