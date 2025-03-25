# OECD Healthcare Spending Analysis

This project explores the relationship between government healthcare expenditure and health outcomes, focusing on average life expectancy across OECD countries. It was developed as a final project for Harvard’s COMPSCI 109A: Introduction to Data Science.

## 📊 Project Objective

To answer the question:  
**"How effective is healthcare spending in improving a country's life expectancy, controlling for economic and educational factors?"**

## Key Concepts

- Panel data analysis
- Multiple linear regression
- Multicollinearity diagnostics (VIF)
- Regularization: LASSO and Ridge
- Polynomial regression
- Data cleaning and visualization
- Fixed effects for country and year

## 🛠Tools & Technologies

- **Python**
- `pandas` for data wrangling  
- `sklearn` for regression and model evaluation  
- `matplotlib` and `seaborn` for visualization  
- OECD Public Finance and Life Expectancy datasets  
- Jupyter Notebook for development


## 🔍 Findings

- Healthcare expenditure alone is a weak predictor of life expectancy.
- Multicollinearity among spending categories (e.g., GDP, education) complicates modeling.
- Regularization methods improved model interpretability.
- Polynomial terms revealed diminishing returns on healthcare spending in some contexts.
- U.S. healthcare spending patterns diverge significantly from other OECD countries.

## Future Work

- Apply clustering to group countries by healthcare effectiveness.
- Extend model with additional health outcome metrics (e.g., infant mortality).
- Explore dynamic panel regression or time-series decomposition.

## Author

**SeoYoung Ha**  

