# Risk-Return-Analysis

This program will allow clients to keep track of their investment portfolios and help them make profitable decisions based off of market data. This will allow users to build portfolios through algorithms. In this case, we are analysing 4 different new investment options.<br />

Users will be able to determine which of the funds have the most investment potential based off of key factors like daily returns, standard deviations, sharpe ratios, and beta
 
## Technologies

Please remember to import the following before running this code:<br />


-import pandas as pd<br />
-import numpy as np<br />
-from pathlib import Path<br />
-%matplotlib inline<br />
 
---
 
## Installation Guide
 
Before running the application first install the following dependencies:<br />

-Pandas<br />

-Python 3<br />


 
---
 
## Findings/Analysis (Explain yourself and why you chose to code this way)
 
I started by setting the correct path to the data file that is needed for this program and gave the dataframe a new name. The daily returns for all the data for every firm including the S&P 500 were calculated and all the NaN values were dropped and plotted. The cumulative daily return values were then calculated and plotted in line plot as well as box plot to analyz volatility. A new dataframe was then created that included all 4 firms but with the S&P 500 removed. Daily returns, annualized standard deviation, day rolling standard deviation, sharpe ratio, variance, covariance, and beta were then calculated and plotted as well. The 60 day rolling period was used for the covariance and beta. 2 funds were chosen to compare with the S&P 500 and those two were Berkshire Hathaway and Tiger Global.
 
---
 
## Contributors
 
Jeffrey Liu : Dev

UCB Provided Initial Starter Code


---
 
## License
Trilogy Technology 
UCB Fintech Extension Program
