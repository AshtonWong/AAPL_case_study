# AAPL_case_study
## The impact of earnings reports on short-term stock price movement.

This project investigates how **Apple Inc's (Ticker: AAPL)** earnings report announcements influence its stock price movements in the short term. Using historical stock data and earnings reports, the study analyzes stock price changes 1, 5, and 10 days after earnings announcements. The analysis follows a comprehensive data analytics process, from formulating a question to preparing, cleaning, analyzing, and sharing actionable insights.

**This project includes:**

📊 Data collection from Investing.com (price data) and AlphaQuery.com (earnings data)  
🧹 A documented data cleaning and transformation process  
📉 Statistical analysis of earnings surprises vs. AAPL stock returns  
📈 Visualizations built using Tableau to highlight trends and correlations  
✅ Key insights to help understand how investors respond to AAPL earnings announcements  

### Problem Statement
The question which this analysis aims to answer is: **How does Apple's stock price react to earnings report announcements in the short term?** Specifically, we examine the stock price movements 1, 5, and 10 days following these announcements.

### Data Sources
**Stock Prices**: Historical AAPL closing prices were sourced from [Investing.com](investing.com).  
**Earnings Reports**: Earnings per Share (EPS) data was obtained from [AlphaQuery.com](investing.com).

### Data Preparation
The data was gathered, cleaned and organized in Microsoft Excel to ensure consistency and relevance. Columns that were not needed were removed, and missing values were handled appropriately. New columns were created for calculation purposes along with columns that will be used for data analysis and visualization.

The data used includes key fields such as:
- **Annoucement Date**: Date of earnings announcement.
- **Closing Price**: Apple's closing stock price on the given date.
- **Estimated EPS**: Analysts' estimated earnings per share before the announcement.
- **Actual EPS**: The actual earnings per share reported by Apple.

The following new columns was used for data analysis and visualization:
- **EPS Surprise**: The difference between the actual and estimated EPS.
- **% Price Change**: The percentage change in stock price 1, 5, and 10 days after the earnings announcement.

### Data Analysis
Various interactive visualizations were created in Tableau to explore the relationship between earnings surprises and stock price movements.

The visualizations include:
- **Scatter Plot**: Shows the correlation between EPS surprise and percentage change in stock price.
- **Box-and-Whisker Plots**: Display the volatility of price changes 1, 5, and 10 days after earnings.

### Key Insights
There is no correlation found between EPS suprise and AAPL's stock movement. However, stock price volatility tends to spike as the earnings date approaches, especially when there's a significant difference between estimated and actual EPS.











