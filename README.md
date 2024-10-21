# PracticePanel
Data: 
  Unemployment rates and GDP(Constant 2015 US$) from World bank data
  Period of study: 2013 to 2023
  Countries: G7: Canada, France, Germany, Italy, Japan, UK, US and EU 
Question: Effect of GDP on unemployment.
Methodolgy:
  Data imported 
  GDP and Unemployment data merged based on Country and Year
  Data converted to panel data frame
  Summarised panel data
  Scatter plot using ggplot2
  Conversion of data to log (interpretation in elasticity and adjusting for non-linearity)
  Regression analysis
    For every 1% increase in GDP, Unemployment decreases by 0.1% and is statistically insignificant at 5% level of significance. Fail to reject null Hypothesis (no relation between the variables). Adjusted R-square is also very low.
  Run Fixed Effects model
  Run Random effects model
  Run the Hausman test to choose the model.
    p-value <0.05 --> Reject the null hypothesis
    Thus, individual effects are correlated with predictors (Fixed effects model)
    For every 1% increase in GDP, Unemployment decreases by 3.06% and is statistically significant. R-squared value is above 0.5. 

  
