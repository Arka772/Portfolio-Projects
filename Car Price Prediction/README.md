# Car Price Prediction

## Project Overview

This project involves building a machine learning model to predict the price of cars based on various features such as engine size, mileage, horsepower, and more. The goal is to provide an accurate estimate of the price for a given car based on its attributes.

### Objectives
- Analyze the relationship between car features and their prices.
- Develop a predictive model to estimate car prices.
- Evaluate model performance using various metrics.
- Handle outliers and apply statistical tests to improve model accuracy.

### Tools & Skills Used
- **Jupyter Notebook (Python)**: Data Analysis, Model Development
- **Libraries**: pandas, numpy, scikit-learn, matplotlib
- **Skills**: Machine Learning, Feature Engineering, Regression Analysis, Outlier Treatment, Statistical Tests (ANOVA, Correlation Analysis)

### Dataset

The dataset includes information on cars, including attributes such as:
- **Car Make and Model**: The manufacturer and model of the car.
- **Engine Size**: The size of the car's engine (in cc).
- **Mileage**: The total distance the car has been driven.
- **Horsepower**: The car's engine power.
- **Price**: The price of the car (target variable).

### Key Steps

1. **Exploratory Data Analysis (EDA)**:
   - Analyzed the distribution of key features like Mileage, Engine Size, and Horsepower.
   - Visualized relationships between features and the target variable (Price).

2. **Feature Engineering**:
   - Created new features based on existing data to improve model accuracy.
   - Handled outliers in variables such as Horsepower, Peak RPM, and Engine Size to prevent model bias.

3. **Outlier Treatment**:
   - Replaced outliers with logical values based on statistical analysis of the dataset.

4. **Statistical Tests**:
   - Conducted ANOVA and correlation analysis to identify the strongest predictors of car price.
   - Selected final features for model building based on the results of these tests.

5. **Model Development**:
   - **Linear Regression**: Used as a baseline model.
   - **Decision Tree Regression**: Improved performance by capturing non-linear relationships.
   - **Random Forest Regression**: Used for further model enhancement.
   - **XGBoost**: Provided the best predictive power in terms of accuracy.

6. **Model Evaluation**:
   - Metrics such as R-Squared, Mean Accuracy, and Median Accuracy were used to evaluate model performance.
   - Applied 10-fold cross-validation to ensure model generalization.

### Final Results

- **Linear Regression**:
  - **R-Squared**: 0.910
  - **Mean Accuracy on test data**: 84.10%
  - **Median Accuracy on test data**: 85.42%
  - **Final Average Accuracy (10-fold Cross Validation)**: 73.03%

- **Decision Tree**:
  - **R-Squared**: 0.897
  - **Mean Accuracy on test data**: 84.72%
  - **Median Accuracy on test data**: 89.36%
  - **Final Average Accuracy (10-fold Cross Validation)**: 81.17%

- **Random Forest**:
  - **R-Squared**: 0.930
  - **Mean Accuracy on test data**: 86.46%
  - **Median Accuracy on test data**: 91.47%
  - **Final Average Accuracy (10-fold Cross Validation)**: 83.29%

- **XGBoost**:
  - **R-Squared**: 0.985
  - **Mean Accuracy on test data**: 87.13%
  - **Median Accuracy on test data**: 91.40%
  - **Final Average Accuracy (10-fold Cross Validation)**: 83.56%

### Full Jupyter Notebook

You can view the full code for this project in the Jupyter Notebook here: [Car Price Prediction (Jupyter)](./CarPricePred.ipynb).


