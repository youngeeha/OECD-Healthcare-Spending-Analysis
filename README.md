{\rtf1\ansi\ansicpg1252\cocoartf2821
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # OECD Healthcare Spending Analysis\
\
## Overview\
This project analyzes the impact of healthcare expenditure on life expectancy across OECD countries using panel regression models, exploratory data analysis (EDA), and regularization techniques.\
\
## Project Objectives\
- Evaluate how effectively healthcare spending predicts life expectancy.\
- Control for confounding variables like GDP per capita and education spending.\
- Address multicollinearity through techniques like LASSO and Ridge regression.\
\
## Data Sources\
- [OECD Public Finance Dataset](https://data.oecd.org)\
- [OECD Life Expectancy Dataset](https://data.oecd.org)\
- [OECD Potential Years of Life Lost](https://data.oecd.org)\
\
## Methodology\
- Data cleaning and exploratory data analysis using `pandas` and `numpy`.\
- Regression analysis and diagnostics (multicollinearity detection, VIF analysis).\
- Regularization techniques (LASSO, Ridge) and polynomial regression to capture complex relationships.\
\
## Results\
- Visualization of country-specific healthcare expenditure and life expectancy trends.\
- Insights on model performance (R-squared, Adjusted R-squared, model validation).\
\
## Installation\
```bash\
pip install -r requirements.txt\
}