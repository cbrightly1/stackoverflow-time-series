# Understanding the Growth in Data Science StackOverFlow Questions
A time series analysis of the StackOverflow question counts for popular data science topics. Includes SARIMA and VARMA modeling for mulitvariate time series in R. Created for the time series course in the Master of Statistical Practice program.

Authors: Alana Willis, Clare Cruz, Dan Nason, & Megan Christy
Department of Statistics and Data Science
Carnegie Mellon University

# Introduction
> StackOverflow is a public question-forum that is popular among data scientists and programmers. In this analysis, it is used to quantify the use of programming languages, such as Python and R, and data science topics, such as Regression and Time Series. Using time series modeling methods on monthly question counts of such languages and topics, we hope to see which data science topics significantly contribute to the number of StackOverflow questions for R and Python and which tool between R and Python has the greatest predicted growth from 2019 to 2021.

# Data
> The dataset used for analysis was obtained from Kaggle and includes the monthly question counts from December 2011 to December 2019 for 82 data science tags. 

# Modeling
> We began our analysis by exploring the data through several time series visualizations, building univariate SARIMA models for the R and Python series to identify complex patterns of trend and seasonality, and finally building multivariate VAR models in an attempt to answer our research questions. 

# Results
> Based on our analysis we found that Python is forecasted to have a 17.97% growth rate from December 2011 to December 2019 while R is forecasted to have a 26.24% growth rate. We also concluded that R has an overall better fit with the data science topics than Python with Classification and Cluster Analysis as significant predictors. We believe that the difference in results between Python and R could be attributed to the fact that R is primarily used for statistical modeling while Python has many other uses, such as software engineering tasks. 

# Discussion
> One major limitation of our analysis is that we chose the variables for our models based on intuition and previous experiences. Thus, there may be better features to predict Python and R question counts. With more time, we would like to extend the time frame of our analysis by including data from 2020 and 2021 to verify the results of our model forecasts. Overall, we believe this analysis provides informative insights on the usage of data science methods in Python and R and how the use of these tools for data science is predicted to grow.
