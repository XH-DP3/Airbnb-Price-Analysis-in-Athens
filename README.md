# STAT 301 Project: Airbnb Price Analysis in Athens
This project was developed as part of STAT 301: Statistical Modelling for Data Science at UBC.
It explores the factors influencing Airbnb prices in Athens, Greece, through a complete data science workflow, from acquiring data online to presenting conclusions in a reproducible Jupyter Notebook report.

## Stage 1
In this stage, I completed the initial exploration of the Airbnb dataset for Athens.
I downloaded the data from the web, cleaned and wrangled it into a tidy format, and created a descriptive summary of all variables, including their names, types, and data sources.
I identified redundant or irrelevant variables in a short Pre-selection of Variables section.
Then, I formulated my scientific question regarding how different property and location features relate to Airbnb listing prices, and specified the response and explanatory variables.
Finally, I performed exploratory data analysis and visualization, creating an informative multi-variable plot to investigate potential relationships and patterns that will guide later modelling.

## Stage 2
In this stage, I reviewed all variables from Stage 1 and identified a subset of predictors that were both relevant and interpretable. I removed variables that were redundant, overly correlated, or not meaningful for price prediction.
Next, I selected Multiple Linear Regression (MLR) as the modelling approach. I justified this choice based on the continuous nature of the response variable (listing price in USD) and the preliminary patterns observed in the EDA, where several predictors appeared to exhibit linear or approximately linear relationships with price.
After building the model, I interpreted the signs and magnitudes of the estimated coefficients to determine how each selected predictor influenced Airbnb prices. I examined statistical significance and practical significance, and verified whether the model aligned with intuition from the EDA. These interpretations helped identify which property or host characteristics most strongly contribute to higher or lower listing prices.
