# Project Report
## Real-World Health Data Analysis and Prediction

### 1. Introduction
Data science is increasingly used in healthcare research to identify patterns in patient-related measurements and support analytical decision-making. This project demonstrates an end-to-end workflow using a real-world health dataset.

### 2. Objective
The objective is to explore baseline health-related measurements and predict a quantitative measure of disease progression one year after baseline.

### 3. Dataset
The project uses the Scikit-learn Diabetes dataset. It contains 442 observations, 10 baseline features, and a quantitative target.

### 4. Data Preparation
The dataset was inspected for missing values, duplicate rows, data types, and descriptive statistics. The data is already numerical and standardized, so unnecessary transformations were avoided.

### 5. Exploratory Data Analysis
Histograms were used to understand distributions. A correlation heatmap was used to study relationships between variables. A scatter plot was used to visualize the feature most strongly correlated with the target.

### 6. Machine Learning
Two regression models were trained:
- Linear Regression
- Random Forest Regression

The data was divided into training and testing sets using an 80:20 split.

### 7. Evaluation
Models were evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² score

### 8. Insights
The analysis provides a quantitative view of the relationships between baseline measurements and disease progression. Random Forest feature importance provides another way to inspect which variables contribute to model predictions.

### 9. Limitations
The dataset is relatively small and is intended for research/educational machine-learning use. The model is not a clinical diagnostic tool.

### 10. Conclusion
The project demonstrates the complete data-science pipeline: data loading, quality checking, exploratory analysis, visualization, model training, evaluation, feature importance, and reporting.
