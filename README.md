# Regression
The goal of this assignment is to apply various regression techniques in supervised learning to predict California housing prices. By using real-world data, we aim to compare the performance of different models and identify the most effective one.
Dataset

Source: California Housing Dataset from sklearn.datasets

Description: The dataset includes information about different housing features in California, such as:

Median Income

House Age

Average Rooms

Average Bedrooms

Population

Households

Latitude

Longitude

Target: Median House Value

Technologies Used

Programming Language: Python

Libraries:

pandas, numpy (Data Manipulation)

matplotlib, seaborn (Visualization)

scikit-learn (Machine Learning Models)

Jupyter Notebook (Development Environment)

Project Structure

ML_Assignment_3/
├── ML_Assignment_3.ipynb
├── README.md
└── requirements.txt (optional)

Methodology

1. Loading and Preprocessing (2 Marks)

Data Loading: Used fetch_california_housing() from sklearn.datasets.

Conversion: Converted to a Pandas DataFrame for better handling.

Missing Values: Checked and handled (if any).

Feature Scaling: Standardization using StandardScaler for better model performance, especially for algorithms like SVR.

2. Regression Algorithms Implementation (5 Marks)

Implemented the following models:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Support Vector Regressor (SVR)

For each model:

Provided a brief explanation of the algorithm.

Justified its suitability for the dataset.

Trained and tested the model.

3. Model Evaluation & Comparison (2 Marks)

Metrics Used:

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

R-squared Score (R²)

Comparison: Identified the best and worst performing models based on the evaluation metrics.

4. Timely Submission (1 Mark)

Well-documented code with clear markdown explanations.

Submitted via GitHub.

Results & Analysis

Best Performing Model: Random Forest Regressor (due to its ability to handle non-linearity and prevent overfitting).

Worst Performing Model: Linear Regression (due to its simplicity and inability to capture complex relationships).

Conclusion

This project demonstrates the application of various regression models to predict real-world data effectively. Through model evaluation, Random Forest Regressor was identified as the most suitable model for this dataset.
