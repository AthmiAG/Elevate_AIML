Task 3 – Simple & Multiple Linear Regression

Objective
To implement and understand simple and multiple linear regression using a real-world housing dataset. Evaluate the model and interpret its output.

Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Joblib  

Steps Performed

1. Loaded the housing dataset using pandas.
2. Cleaned the dataset by removing NaN and infinite values.
3. Encoded the categorical ocean_proximity column using LabelEncoder.
4. Visualized feature correlations using a heatmap.
5. Simple Linear Regression:
   - Used median_income as the sole feature to predict median_house_value.
   - Split data into train-test sets.
   - Trained using LinearRegression.
   - Evaluated using MAE, MSE, RMSE, and R².
   - Plotted the regression line and residuals.
6. Multiple Linear Regression:
   - Used all numerical features to predict median_house_value.
   - Evaluated similarly using MAE, MSE, RMSE, and R².
   - Printed coefficients for interpretation.
   - Plotted residual distribution.
7. Saved the final model using joblib.

Key Insights

- Median income is the most influential feature for predicting house value.
- RMSE helps better understand real-world error magnitude.
- Residual plots confirm reasonably normal error distribution.
- Including all features marginally improves model performance compared to using just one.

Output Files

- multiple_linear_regression_model.pkl – Trained model file
- Regression plots and residual distributions (through matplotlib/seaborn)
- DOCX report: Linear_Regression_Report_Housing.docx

Conclusion

This task successfully demonstrated the working of both simple and multiple linear regression using Scikit-learn. The added visualizations and metrics enhance understanding and model trust.
