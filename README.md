# RainCast
Rainfall Forecasting using Machine Learning

This project includes Python scripts for forecasting rainfall using regression models, 
evaluating performance with metrics, and visualizing results. Models include Linear Regression, 
Decision Tree, Random Forest, K-Nearest Neighbors, and SVM.

Evaluation metrics used:
- R² (Coefficient of Determination)
- RMSE (Root Mean Squared Error)

Visualization tools:
- Bubble Plot for district-wise RMSE and R² representation.

Setup and Installation
1. Prerequisites: Ensure Python 3.8+ and pip are installed.
2. Install Required Libraries
numpy
pandas
scipy
scikit-learn
matplotlib
seaborn
geopandas

Steps to Run the Code
1. Import Data 
- Use a CSV file containing features and a target variable (e.g., rainfall).

2. Analyze Correlation
- Perform linear regression between Madhya Pradesh and Chhattisgarh rainfall data.
- Plot Scatter diagram

3. Calculate partial autocorrelation
- Use the pacf function to analyze lag effects
- Visualize the lag plot

4. Feature Engineering 
- Select the optimal lag value
- Split the data into training (X_train, y_train) and testing (X_test, y_test)

5. Train Models Individually
- Train Linear Regression, Decision Tree, Random Forest, K-Nearest Neighbors, and SVM models
- Evaluate performance using metrics

6. Hyperparameter Tunning
- Use GridSearchCV to find optimal hyperparameters for each model

7. Run Tuned Models and Evaluate
- Train models with the best hyperparameters and evaluate performance

8. Forecasting
- Use the best-performing model for future rainfall predictions
 
9. Generate Visualizations:
   - Create district-wise evaluations for RMSE and R².
   - Plot a Bubble Chart for R² and RMSE

File Descriptions
- MP_rainfall.ipynb: Script for training models, calculating metrics, and creating visualizations
- monthly_mp.csv: Dataset for Madhya Pradesh rainfall (training and testing)
- Other Files: Can be added as per your data requirements

- 

Results
- Evaluation metrics are saved in a DataFrame and visualized.
- Bubble Plot: Displays RMSE and R² by district.

Contact
For inquiries or support, contact:
- Name: Soumya Kundu
- Email: soumya24@iiserb.ac.in
