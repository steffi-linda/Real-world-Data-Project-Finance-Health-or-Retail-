# Real-World Health Data Project

## Diabetes Disease Progression Analysis & Prediction

### Overview
This project analyzes the Scikit-learn Diabetes dataset and builds machine-learning regression models to predict a quantitative measure of disease progression one year after baseline.

> **Important:** The target is a disease-progression measure and is not a medical diagnosis.

## Objectives
- Explore a real-world health dataset
- Perform data quality checks
- Analyze feature distributions
- Study correlations
- Visualize relationships
- Train regression models
- Compare model performance
- Analyze feature importance
- Present practical conclusions

## Dataset
The project uses the built-in **Diabetes dataset** distributed with Scikit-learn. The included CSV is provided for easy Jupyter execution.

### Dataset contents
The dataset contains 10 baseline features:
- age
- sex
- bmi
- bp
- s1
- s2
- s3
- s4
- s5
- s6

The `target` column is a quantitative measure of disease progression one year after baseline.

## Models
1. Linear Regression
2. Random Forest Regression

## Evaluation Metrics
- MAE – Mean Absolute Error
- RMSE – Root Mean Squared Error
- R² – R-squared

## Visualizations
- Target distribution
- Feature distributions
- Correlation heatmap
- Strongest-feature scatter plot
- Actual vs predicted plot
- Feature importance
- Residual analysis

## How to Run
1. Extract the project ZIP.
2. Open Anaconda Prompt.
3. Run `jupyter notebook`.
4. Open `Health_Data_Analysis_and_Prediction.ipynb`.
5. Select **Kernel → Restart & Run All** or run the cells from top to bottom.
6. Keep `diabetes_real_world_dataset.csv` in the same folder as the notebook.

## Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook.
