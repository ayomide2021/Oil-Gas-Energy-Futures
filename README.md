# Oil-Gas-Energy-Commodities Exploratory Data Analysis
 
# Introduction
Over the years, fossil fuels have played significant roles in supplying energy for heating and power generation to the human population. Various factors, including global demand, government policies, economic considerations, and technological advancements, have influenced energy availability. In this analysis, I employ an up-to-date dataset concerning futures related to major fossil fuels to offer the following: Trend Analysis and Market Dynamics: analyse and scrutinize price fluctuation patterns to predict future market trends in the energy industry. Trading and Investment Strategies: utilize the dataset to test trading and investment strategies based on energy fuel dynamics. Risk Management: provide insights into hedging and managing portfolio risks
My choice of dataset is deliberate, as it aligns with my experience in the Oil and Gas Industry in Europe and Africa. 

# Skills
•	Data manipulation with Pandas

•	Data Visualization with Matplotlib, Plotly and Seaborn

•	Data Cleaning and Preprocessing

•	Data Storytelling and Communication

# Objectives
1.	To evaluate the volatility of each commodity over the years
2.	To prepare a correlation matrix and heatmap of the commodities
3.	To visualise the price trend over time for each commodity

# Data source
The dataset used in this project was obtained from an online source on Kaggle. I downloaded the dataset in CSV format and subsequently imported it into Python using the Pandas library. The dataset was then subjected to a series of data cleaning, analysis, and visualization steps. 
The dataset comprises 8 columns for the combined data, whereas the individual data contains 6 columns.
The following text describes the columns. It provides a detailed explanation of what information is contained in each column. Please note that any errors in spelling, grammar, or punctuation have been corrected.
1. Date: Trading Days from 2000 to 2023. Format: YYYY-MM-DD.
2. Open: Market's opening price for the day.
3. High: Peak price during the trading window.
4. Low: Lowest traded price during the day.
5. Close: End of day(EOD) prices.
6. Volume: The quantity of contracts traded during the trading period.
7. Ticker: The unique market quotation symbol for the commodity.
8. Commodity: Indicates the type of fuel to which the future contract is related, such as crude oil or natural gas.

This process of data extraction and preparation forms the foundation for the subsequent data analysis and visualization steps in the project.

# Data Transformation/Cleaning
Data cleaning and transformation were executed within a Jupyter Notebook using the Pandas library. To ensure the dataset's integrity, each column was meticulously inspected through a for-loop, confirming the absence of empty cells or errors. The dataset is clean with no missing or NaN value. The date data was converted to datetime format for more meaningful and accurate time-series analysis and visualization.

# Preliminary data exploration
As part of the project, I conducted an initial Exploratory Data Analysis (EDA) and utilized statistical data visualization techniques to gain insights from the dataset. The key steps in this phase included: histogram distribution of commodities over time, trading volume of commodities over time, price trend and box plot distributions. By conducting this initial EDA and employing these statistical data visualization methods, I aimed to uncover significant patterns, anomalies and insights within the dataset.

# Data Modelling
A new column was created for the daily price per cent change over time for all commodities. This new column is particularly useful for the visualization of changes in daily price trends over time.  


# Analysis
Analysis was done using simple visuals like histogram and line plots. A correlation matrix and heat map were also created to visualize the pair-wise correlations between commodities. 
# Daily price per cent change over time for all commodities
![G1](https://github.com/ayomide2021/Oil-Gas-Energy-Futures/assets/83126882/9035f830-7410-485e-9a5a-36da4e1eedef)
# log scale visualization
![newplot (1)](https://github.com/ayomide2021/Oil-Gas-Energy-Futures/assets/83126882/8065e8a3-361a-4353-a072-37873a022e23)
# Volatility of commodities
![G2](https://github.com/ayomide2021/Oil-Gas-Energy-Futures/assets/83126882/f719cb6c-a10b-446f-b707-9a533c9c5f47)

# Pairwise correlations of commodities
![G3](https://github.com/ayomide2021/Oil-Gas-Energy-Futures/assets/83126882/58b3a849-8085-47e4-8275-8228fe68cb27)


# Conclusions/recommendations
1. The log-scale plot reveals a close relationship between the price trends of Brent oil and crude oil.
2. Crude oil exhibits the highest volatility while heating oil displays the least. The significant volatility in oil prices can be largely attributed to the negative oil prices experienced in April 2020.
3. The correlation matrix illustrates strong correlations between all oil derivatives and crude oil while indicating weak correlations with natural gas. This observation implies that the market dynamics of natural gas differ significantly from those of crude oil.
4. The long-term price trends underscore the impact of various global events, including political factors and changes in demand, on the dynamics of commodities.¶
5. It would be useful to improve the quality of this project in the future by adding predictive modelling techniques or machine learning tools to make mid-to long-term price predictions of the commodities. 


