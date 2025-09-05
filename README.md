Project Title

Stock Price Analysis of Reliance Industries (Excel Project)

-Objective

The goal of this project is to analyze the historical stock price performance of Reliance Industries using Microsoft Excel.
The analysis includes calculating daily returns, moving averages, annualized return & volatility, and visualizing stock trends.

📂 Data Source

Data downloaded from NSE
 → Historical Data

Period covered: September 2024 – September 2025

Columns used: Date, Adjusted Close Price

🔎 Steps Performed

Data Cleaning

Selected Date and Adjusted Close Price columns.

Renamed Adjusted Close Price → Price.

Daily Returns Calculation

Formula:

=(Current Price – Previous Price) / Previous Price


Shows percentage change in stock price each day.

Moving Averages (MA20 & MA50)

Used Excel =AVERAGE(range) function.

MA20 (short-term trend) and MA50 (medium-term trend) plotted.

Visualizations

Line Chart: Stock Price with MA20 & MA50.

Histogram: Distribution of Daily Returns.

Additional Metrics

Annualized Return:

=AVERAGE(Daily_Returns)*252


→ -76.17%

Annualized Volatility:

=STDEV(Daily_Returns)*SQRT(252)


→ 102.23%

📈 Results & Insights

📉 Stock Trend: Reliance stock during this period showed a downward trend overall, with very sharp fluctuations.

📊 Daily Returns: Most daily returns were within -2% and +2%, but some outliers indicate sudden movements.

📈 Annualized Return: -76.17%, suggesting a negative return for the period studied.

⚡ Annualized Volatility: 102.23%, indicating very high risk and instability.

📌 Observation: The crossover of MA20 and MA50 highlighted several reversal points, confirming trend instability.