# Private-Construction-Spending-Forecast

# General Overview
In this project, I forecast total private construction spending on manufacturing in CA using 30 years of data from FRED. 

# Use Case
This project provides an example of how to fit a forecasting model with trend, season dummies and cycles. In addition, this project showcases the use of vector autoregressive (VAR) modeling, which is a multivariate time series model that relates current observations of a variable with past observations of itself and past observations of other variables in the system.

# Important Notes
1. You will find instructions for this project in "Project_2_Questions.pdf" and the answers and supporting code in an R Markdown file named "Project_2_Answers.Rmd".
2. All supporting data that is used in my script can be found in the "Supporting_Data" folder, should you be looking to replicate this exact work. 
3. As noted in the assignment instructions, in order for the forecasting model to adequately capture the cyclical dynamics, you will need a large time horizon within the selected data. Therefore, if you are looking to replicate this work with a different data set, it is suggested that you have at least 10 years of observations.
4. In order to fit a VAR model, you will need at least two time-series variables.
