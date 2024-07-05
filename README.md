# Oil-Gas-Energy-Commodities Exploratory Data Analysis
 
# Introduction
Over the years, fossil fuels have played significant roles in supplying energy for heating and power generation to the human population. Various factors, including global demand, government policies, economic considerations, and technological advancements, have influenced energy availability. In this analysis, I employ an up-to-date dataset concerning futures related to major fossil fuels to offer the following: Trend Analysis and Market Dynamics: analyse and scrutinize price fluctuation patterns to predict future market trends in the energy industry. Trading and Investment Strategies: utilize the dataset to test trading and investment strategies based on energy fuel dynamics. Risk Management: provide insights into hedging and managing portfolio risks
My choice of dataset is deliberate, as it aligns with my experience in the Oil and Gas Industry in Europe and Africa. 

# Objectives
1.	To evaluate the volatility of each commodity over the years
2.	To prepare a correlation matrix and heatmap of the commodities
3.	To visualise the price trend over time for each commodity

# Skills
•	Data manipulation with Pandas

•	Data Visualization with Matplotlib, Plotly and Seaborn

•	Data Cleaning and Preprocessing

•	Data Storytelling and Communication


# Data Source and Preparation
The dataset, sourced from Kaggle, was imported into Python using the Pandas library. It contains data from 2000 to 2023 with columns for trading dates, opening and closing prices, daily high and low prices, trading volume, ticker symbols, and commodity types. The dataset was thoroughly cleaned, transformed, and prepared for analysis.
# Data Cleaning and Transformation
Data cleaning was executed using the Pandas library in Jupyter Notebook. Key steps included:

•	Inspecting each column for empty cells or errors

•	Converting date data to datetime format for accurate time-series analysis

# Preliminary Data Exploration
Exploratory Data Analysis (EDA) involved:

•	Histogram distributions of commodities over time

•	Trading volumes over time

•	Price trend analysis and box plot distributions

# Data Modelling
A new column was created for the daily price percentage change over time for all commodities, facilitating visualization of price trends.
# Analysis Techniques
•	Histogram and line plots for visual analysis

•	Correlation matrix and heatmap for visualizing pairwise correlations between commodities


# Analysis
Analysis was done using simple visuals like histogram and line plots. A correlation matrix and heat map were also created to visualize the pair-wise correlations between commodities. 
# Daily price per cent change over time for all commodities
![G1](https://github.com/ayomide2021/Oil-Gas-Energy-Futures/assets/83126882/9035f830-7410-485e-9a5a-36da4e1eedef)
# Log scale visualization
![newplot (1)](https://github.com/ayomide2021/Oil-Gas-Energy-Futures/assets/83126882/8065e8a3-361a-4353-a072-37873a022e23)
# Volatility of commodities
![G2](https://github.com/ayomide2021/Oil-Gas-Energy-Futures/assets/83126882/f719cb6c-a10b-446f-b707-9a533c9c5f47)

# Pairwise correlations of commodities
![G3](https://github.com/ayomide2021/Oil-Gas-Energy-Futures/assets/83126882/58b3a849-8085-47e4-8275-8228fe68cb27)

# Key Findings
1.	Log-Scale Plot: Reveals a close relationship between the price trends of Brent oil and crude oil.
 
2.	Volatility: Crude oil exhibits the highest volatility, with significant fluctuations largely due to the negative oil prices in April 2020. Heating oil displays the least volatility.
   
3.	Correlation Matrix: Shows strong correlations between all oil derivatives and crude oil, indicating similar market dynamics. In contrast, natural gas shows weak correlations with crude oil, highlighting distinct market behaviors.
  
4.	Long-Term Price Trends: Reflect the impact of global events, political factors, and changes in demand on commodity dynamics.
# Recommendations
•	Current Best Model: The simple linear model outperformed others in three of four key metrics, demonstrating efficiency with a prediction time of 0.004 seconds. Its high interpretability makes it suitable for the client’s needs in healthcare services.

•	Future Improvements: Incorporating predictive modeling techniques or machine learning tools could enhance the project's quality, enabling mid-to long-term price predictions for the commodities.

This comprehensive analysis of fossil fuel futures offers actionable insights for market trend prediction, trading strategies, and risk management, aiding stakeholders in making informed decisions and improving resource allocation.



