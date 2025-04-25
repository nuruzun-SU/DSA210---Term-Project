# DSA210---Term-Project

## **The Relationship Between S&P 500 ESG Scores and Their Stock Prices (Annual Return)**

### **Motivation**

Environmental, Social, and Governance (ESG) factors are playing an increasingly central role in modern investment strategies. As ESG performance becomes more relevant to ethical and regulatory standards, investors and analysts seek to understand whether it also has a measurable impact on financial outcomes—especially stock performance.

This project investigates whether companies with higher ESG scores achieve better annual stock returns. By focusing on S&P 500 companies and examining their ESG ratings alongside financial data from January 2023 to August 2024, this research aims to provide insights that help investors, financial managers, and policymakers make informed, sustainability-oriented decisions.

### **Data Source**

The data used in this analysis includes both ESG ratings and historical stock market data:

- **ESG Data**: ESG scores for S&P 500 companies were sourced from platforms like Refinitiv or other reliable ESG providers. For this project, scores announced in **September 2023** were used to evaluate the companies’ sustainability performance.

- **Stock Market Data**: Daily stock prices were collected from platforms like Yahoo Finance. The analysis focused on the price change between **January 3, 2023** and **August 30, 2024**, which was used to calculate each company’s **annual return**.

### **Merging the Data**

To align ESG scores with stock performance data, a structured merging approach was followed:

- **Ticker Symbol**: Each company is matched using its unique stock ticker (e.g., AAPL, MSFT).
- **Timeframe Alignment**: ESG scores published in September 2023 were assumed to reflect sustainability standing over the following period. Stock returns were calculated based on the price difference before and after this ESG rating release.
