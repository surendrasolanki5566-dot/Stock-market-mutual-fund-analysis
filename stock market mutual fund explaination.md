 Mutual Fund Overview & Insights

This mutual fund analysis project focuses on identifying top 30 schemes with high return and low risk using Python, Excel, and Power BI.



To identify top-performing, low-risk mutual fund schemes using data-driven techniques and present insights through a dynamic, professional Power BI dashboard.




 1. Data Cleaning
- Removed unnecessary columns
- Handled missing values
- Standardized numeric formats (returns, expense ratios)

 2. Data Description & Understanding
- Statistical summaries using Pandas: mean, median, mode, min, max, std deviation
- Analyzed fund distributions across return rates, risk levels, and fund age

 3. Data Normalization
- Used `MinMaxScaler` from `sklearn.preprocessing` to normalize numeric fields
- Compared returns and expense ratios on a common scale

 4. Fund Scoring & Ranking
Custom scoring formula based on:
- High 3-Year Returns  
- Low Expense Ratio  
- Moderate Fund Age  
- Consistent 1-Year Return > 0

 5. Final Output – Top 30 Funds
Extracted the Top 30 Mutual Funds with best return-low risk balance  

 