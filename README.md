# car-price-modeling-case-study
Predicting car prices using regression models and evaluating performance with visualization and metrics.
# Car Price Regression Analysis

## Overview
This project explores how different regression models can be used to predict car prices using an automobile dataset.

---

## Approach
- Simple Linear Regression (highway-mpg → price)
- Multiple Linear Regression (multiple features)
- Polynomial Regression (captures non-linearity)
- Model evaluation using plots, R², and MSE

---

## Key Visualizations

### Regression Plot
![Regression Plot](Regression%20Plot.png)

Shows a negative relationship between fuel efficiency and price.

---

### Residual Plot
![Residual Plot](Residual%20Plot.png)

Shows a pattern in residuals, indicating the linear model is not a perfect fit.

---

### Polynomial Fit
![Polynomial Fit](Polynomial%20Fit.png)

Better captures the curved relationship between variables.

---

### 11th-Order Polynomial Fit (Overfitting Example)
![11th Polynomial](11th%20Order%20Polynomial%20Fit.png)

Shows overfitting where the model becomes too complex and unstable.

---

## Key Insights
- Higher highway-mpg → lower price  
- Larger engine size → higher price  
- Linear models are simple but limited  
- Polynomial models improve fit but can overfit  
- Multiple regression gives the best balance  

---

## Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  

---

## Conclusion
Multiple Linear Regression provides the best balance between accuracy and simplicity, while higher-degree polynomial models demonstrate the risks of overfitting.

---

## Author
Diane King
