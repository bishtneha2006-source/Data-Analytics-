# 📘 Day 14

## ✅ Topic Covered
Curve Fitting and Regression Models in R

## 🧠 Summary
Today’s session introduced **curve fitting techniques** to model **relationships between variables**. Curve fitting is essential for **prediction, trend analysis, and understanding how variables interact**. We focused on linear and polynomial regression models, which form the foundation for many statistical and machine learning applications.

## 🔍 New Concepts Learned
- **Linear Model (Polynomial Regression Model)**  
  - Fit a straight line or polynomial curve to data using `lm()`  
  - Polynomial regression allows modeling **non-linear relationships** by including higher-degree terms  
  - Provides coefficients that describe the **relationship strength and direction** between variables  

- **Model Evaluation Techniques:**  
  - Checking **R-squared values** to assess goodness of fit  
  - Examining **residuals** to understand model accuracy  
  - Using **predict()** function to generate predicted values  

- **Applications of Curve Fitting:**  
  - Forecasting trends in time series data  
  - Predicting outcomes based on input variables  
  - Understanding patterns in experimental or observational data  

## 💻 Activity
- Created sample datasets with numeric variables  
- Applied `lm()` to fit linear and polynomial regression models  
- Visualized fitted curves using `ggplot2` with `geom_smooth(method = "lm")`  
- Calculated and interpreted **R-squared values** and residuals  
- Predicted values for new data points using the regression model  

## 🤔 Challenges Faced
- Understanding **degree selection** in polynomial regression  
- Interpreting coefficients for higher-degree polynomial terms  
- Ensuring the model does not **overfit** the dataset  

## 🎯 Key Takeaway
Curve fitting and regression models allow us to **quantify relationships** between variables and make **predictions**. Linear and polynomial models are powerful tools for **trend analysis, forecasting, and data-driven decision making** in R.
