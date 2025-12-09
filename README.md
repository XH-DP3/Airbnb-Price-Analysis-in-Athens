An Inferential Analysis of Factors Influencing Airbnb Prices in Athens
This project was developed as part of STAT 301: Statistical Modelling for Data Science at UBC, consisted of two individually completed stages followed by a collaborative final stage.

It explores the factors influencing Airbnb prices in Athens, Greece, through a complete data science workflow, from acquiring data online to presenting conclusions in a reproducible Jupyter Notebook report.

## Stage 1 (Individual)
In this stage, I was able to: 
- Acquire the Airbnb Athens dataset from the web, clean and wrangle it into a tidy format.
- Generate a descriptive summary of all variables, including names, types, units, and data sources.
- Conduct an initial assessment of variable quality and redundancy in a short Pre-selection of Variables section.
- Formulate my scientific question about how property features, host attributes, and location characteristics relate to Airbnb listing prices.
- Clearly define the response and explanatory variables for later modelling.
- Perform exploratory data analysis and visualization, including a multi-variable plot to study early trends, potential associations, and patterns relevant to model building.
- 
## Stage 2 (Individual)
In this stage, I was able to: 
- Revisit and refine the variable set from Stage 1, selecting predictors that were relevant, interpretable, and not redundant.
- Remove variables that were overly correlated, duplicated in meaning, or lacked conceptual justification for inclusion.
- Choose Multiple Linear Regression (MLR) as the modelling framework, motivated by the continuous response variable and linear patterns observed in the EDA.
- Fit the preliminary model and interpret coefficient signs and magnitudes to understand how each predictor influences Airbnb price.
- Assess statistical and practical significance, and verify whether the model findings aligned with insights from the EDA.
- Identify the key property and host characteristics most strongly associated with variation in listing price.

## Final Report (Group)
The final stage was completed collaboratively with Lexie Wen, Marylyn Yuwono, and Zhenyu Zhong. We carried out the full inferential modelling workflow. During this stage, I contributed primarily to coding, workflow design, and interpretation.

As a team, we were able to:
- Perform an initial Exploratory Data Analysis (EDA) focused on variable distributions, potential outliers, and preliminary relationships between key predictors and listing prices. These insights helped motivate our modelling decisions and guided which variables required transformation or closer examination.
- Split the dataset into a variable-selection set and an inference set to support unbiased inferential conclusions.
- Compute VIF values to diagnose multicollinearity and remove predictors with excessively high VIF scores.
- Construct a full model (after VIF filtering) and propose several reduced models based on interpretability and theoretical justification.
- Perform nested model comparison using F-tests to determine whether reduced models provided a significantly worse fit than the full model.
- Select the best-fitting model and conduct a full set of model diagnostics to assess linearity, non-constant variance, normality of residuals, and influential observations.
- Apply appropriate model fixes (i.e., log transformation of the response) when assumptions were violated.
- Refit the final chosen model on the inference dataset and carry out formal inference, including hypothesis testing and coefficient interpretation.
- Provide a thoughtful discussion of results, highlighting the practical implications of the findings, limitations of our analysis (such as missing variables or sampling constraints), and identifying future directions, such as incorporating additional listing attributes, exploring spatial models, or comparing results across different cities.

My role in this stage focused on developing the modelling workflow, writing and organizing the core R code, and interpreting the regression results of the final analysis.
