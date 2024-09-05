# Iris Dataset Classification

## Project Overview

This project involves building a classification model to predict the species of Iris flowers based on their petal and sepal measurements. The Iris dataset is one of the most well-known datasets in machine learning and is commonly used for classification tasks.

### Objectives
- Classify Iris flowers into one of three species: Setosa, Versicolor, and Virginica.
- Build and evaluate multiple classification models to determine the best-performing model.

### Tools & Skills Used
- **Jupyter Notebook (Python)**: Data Analysis, Model Building
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn
- **Skills**: Data Preprocessing, Classification, Model Evaluation

### Dataset

The Iris dataset includes 150 observations of Iris flowers, with the following features:
- **Sepal Length**: Length of the sepal (in cm).
- **Sepal Width**: Width of the sepal (in cm).
- **Petal Length**: Length of the petal (in cm).
- **Petal Width**: Width of the petal (in cm).
- **Species**: The target variable, which can be one of three species: Setosa, Versicolor, Virginica.

### Key Steps

1. **Data Preprocessing**:
   - Handled missing values (if any), and standardized the features for better model performance.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized the distribution of each feature and explored the relationships between features using pair plots and correlation heatmaps.

3. **Model Development**:
   - **Logistic Regression**: A simple yet effective baseline model for classification.
   - **Decision Tree Classifier**: Captured non-linear relationships between the features.
   - **Random Forest Classifier**: Combined the predictions of multiple decision trees to improve performance.
   - **K-Nearest Neighbors (KNN)**: A distance-based classifier.

4. **Model Evaluation**:
   - Evaluated each model using metrics such as Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
   - Applied **cross-validation** to validate the generalization of each model.

### Final Results

- **Best Model**:: RandomForestClassifier (max_depth=7)
- **Accuracy on Testing Data**: 98%
- **Precision**: 0.98
- **Recall**: 0.98
- **F1-Score**: 0.98


### Full Jupyter Notebook

You can view the full code for this project in the Jupyter Notebook here: [Iris Dataset Classification (Jupyter)](./IRIS.ipynb).
