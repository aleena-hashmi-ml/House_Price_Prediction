House Price Prediction

Project Overview

This project uses Machine Learning regression algorithms to predict house prices based on different housing features.

Problem Type

Supervised Machine Learning – Regression

Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

Dataset

The project uses the California Housing dataset ("housing.csv").

Project Workflow

1. Data Loading
2. Data Understanding
3. Exploratory Data Analysis (EDA)
4. Correlation Analysis
5. Data Preprocessing
6. Handling Missing Values
7. Feature and Target Separation
8. Train-Test Split
9. Feature Scaling
10. Model Training
11. Model Evaluation
12. Model Comparison

Machine Learning Algorithms

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

Model Performance

Model| MAE| R² Score
Linear Regression| 50670.74| 0.6254
Decision Tree| 44180.85| 0.6287
Random Forest| 31639.37| 0.8165
Gradient Boosting| 38248.03| 0.7617

Conclusion

Random Forest Regressor achieved the best performance among the four models, with an R² score of approximately 0.8165.

This project helped explore data analysis, preprocessing, regression algorithms, and model evaluation.

Project Structure

House_Price_Prediction/
│
├── data/
│   └── housing.csv
│
├── House_Price_Prediction.ipynb
└── README.md