# Medical Insurance Cost Prediction

## Overview

This project aims to predict medical insurance costs using a dataset obtained from Kaggle. The dataset contains various features related to individuals' demographics and health conditions, which are used to train a machine learning model to estimate insurance costs. The project involves data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

## Dataset

The dataset used for this project can be found on Kaggle at the following link: [Medical Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance).

## Libraries Used

The following libraries were utilized in this project:

- `NumPy`: For numerical operations and handling arrays.
- `Pandas`: For data manipulation and analysis.
- `Matplotlib`: For data visualization.
- `Seaborn`: For enhanced data visualization.
- `Scikit-learn`: For machine learning model training and evaluation.

## Steps Involved

1. **Data Loading**: The dataset was loaded using Pandas.
2. **Data Preprocessing**: This included handling missing values, encoding categorical variables, and normalizing numerical features.
3. **Exploratory Data Analysis (EDA)**: Visualizations were created to understand the distribution of data and relationships between features, including age, BMI, number of children, and smoking status.
4. **Model Training**: The dataset was split into training and testing sets. A Linear Regression model was trained on the training set to predict insurance costs.
5. **Model Evaluation**: The model's performance was evaluated using R-squared (R²).

## Results

The R-squared (R²) value for the prediction of the training data is 75% and that of the test data is 74%.

## Conclusion

This project demonstrates the process of building a medical insurance cost prediction model using machine learning techniques.

## Installation

To run this project, you will need to install the following libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
