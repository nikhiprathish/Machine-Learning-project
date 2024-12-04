# Machine-Learning-project
**Car Price Prediction in the US Market**
**Overview**
This project involves building regression models to predict car prices in the US market using a dataset containing various car attributes. The aim is to help a Chinese automobile company understand the factors affecting car prices and leverage this knowledge to compete effectively in the market.
**Business Objective**
**The project focuses on:**
Identifying the significant factors affecting car prices in the US market.
Building and evaluating regression models to predict car prices.
Analyzing feature importance and optimizing the best model through hyperparameter tuning.
Workflow
****The project is divided into the following steps:
1. **Data Preprocessing**
Loading Dataset: The dataset was loaded and inspected for quality.
Data Cleaning:
Handled missing values.
Removed duplicates.
Detected and treated outliers using boxplots and Z-scores.
Feature Engineering: Encoded categorical variables using one-hot encoding and scaled numerical features using MinMaxScaler.
2. **Model Implementation**
Implemented and compared the following regression algorithms:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor
3. **Model Evaluation**
Models were evaluated using:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R2 Score
4. **Feature Importance Analysis**
Used feature selection techniques like SelectKBest and Random Forest feature importance to identify the most significant variables influencing car prices.

5. **Hyperparameter Tuning**
Optimized the best-performing model (Random Forest Regressor) using GridSearchCV for parameters like:

n_estimators
max_depth
min_samples_split
Results
Best Model: Random Forest Regressor with optimized parameters.
R2 Score after tuning: Achieved a score close to 0.63, indicating a strong predictive performance.
Key Factors Affecting Price: Engine size, horsepower, car weight, and fuel type were identified as critical factors.
