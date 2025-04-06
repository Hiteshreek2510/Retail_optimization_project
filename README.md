#  Optimizing Retail Inventory with Multi Agents
## Problem Statement: Optimizing Retail Inventory with Multi Agents
The goal is to design a Multi-agent system for forecasting sales and managing supply chains in a retail environment .The system should process real-time or historical sales data, generate demand forecasts and coordinate between various agents such as
-	Store agent –Sends daily sales data
-	Coordinator agent- Oversees communication and decision-making
-	Forecasting agent- Analyzes data and predicts future demand 
-	Warehouse Agent- Manages inventory updates
-	Supplier Agent – Handles restocking based on demand
### The Conceptual Multi-Agent System:
([MULTI-AGENT Architecture.docx](https://github.com/Hiteshreek2510/Retail_optimization_project/blob/main/MULTI-AGENT_Architecture.docx))
## Solution overview:
This project implements a time series forecasting model to predict future product demand based on historical sales. The forecasted values are used to inform inventory decisions, aiming to balance supply and demand effectively 
# Tools and technologies:
-	Python, Pandas, Statsmodels (ARIMA)
-	Matplotlib/Seaborn for visualization
-	StarUML for architecture diagram
-	Kafka(conceptual)
## Methodology
-	Data collection: Historical sales data provided in CSV format
-	Data Preprocessing: Checked for missing values, outliers, trends, seasonality
-	Model Selection: ARIMA was selected for its efficiency with structured time-series data and its strong performance with limited data volume
-	Model evaluation: Evaluated using metrics like RMSE and AIC. The model forecasts suitable for weekly or monthly inventory planning.
# Model Accuracy 
-	MAE: 1085.79 - average error
-	RMSE: 1331.59 - root mean square error (penalizes large errors)
-	MAPE: 17.16% -  percent error (lower is better; this is decent)
### The ipynb file is in the zip folder
([Link to file](https://github.com/Hiteshreek2510/Retail_optimization_project/blob/main/Hackathon_Retail_optimize.zip))
### Output
([OUTPUT FILE](https://github.com/Hiteshreek2510/Retail_optimization_project/blob/main/forecast.csv))
## Conclusion
This project focuses on demand forecasting a critical skill in data science, while real-time system integration is not implemented,  a clear   architectural plan is presented, demonstrating of scalable solutions. The ARIMA model is used to predict or forecast the demand of products for future .The architecture can be supported by Kafka middleware for futuristic work

