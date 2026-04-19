# ACC102 Mini Assignment - Track 2
## Microsoft vs Apple Stock Performance Analysis (2023)

### 1. Project Overview
This project compares the 2023 stock performance of Microsoft (MSFT) and Apple (AAPL) using WRDS CRSP data. The goal is to analyze risk, return, trend, and correlation for retail investors.

### 2. Data Source
- Database: WRDS CRSP Daily Stock File
- Access Date: 2026-04-19
- Permno: 10107 (Microsoft), 14593 (Apple)
- Period: 2023-01-01 to 2024-01-01

### 3. Methods
- Data extraction via WRDS SQL
- Data cleaning (drop missing values)
- Descriptive statistics (price mean, max, min)
- Daily return & annualized volatility (risk measurement)
- 30-day moving average for trend identification
- Price correlation analysis
- Cumulative return comparison
- Visualization with matplotlib

### 4. Key Results
- Microsoft Volatility: 25.13%
- Apple Volatility: 19.95%
- Price Correlation: 0.948
- Microsoft Cumulative Return: ~1.60x
- Apple Cumulative Return: ~1.56x

### 5. Key Findings
- Microsoft had higher volatility (risk) but higher total return in 2023.
- Apple was more stable and conservative.
- The two stocks are strongly positively correlated.
- Microsoft showed a stronger upward trend.

### 6. How to Run
1. Open the .ipynb file in Jupyter Notebook
2. Run all cells sequentially
3. Input your WRDS username and password

### 7. Limitations
- Only one year of data
- Focus on price only
- No fundamental financial ratios included

### 8. Demo Video
https://www.bilibili.com/video/BV1PqoFB7EiA/
