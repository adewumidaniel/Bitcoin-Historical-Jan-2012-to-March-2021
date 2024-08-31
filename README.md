# Bitcoin Historical Data Jan 2011 to December 2017

### Project Overview

Bitcoin is the longest running and most well-known cryptocurrency, first released as open source in 2009 by the anonymous Satoshi Nakamoto. Bitcoin serves as a decentralized medium of digital exchange, with transactions verified and recorded in a public distributed ledger (the blockchain) 
without the need for a trusted record keeping authority or central intermediary. The analysis shows the trend in volume (BTC) and (Currency) by month in each year including weight of price by month to determine which month of the year has the highest volume by BTC and Currency base on the opening and closing for the month.

![image](https://github.com/user-attachments/assets/3c2a9b33-0a17-464c-b0fb-4d7a56243f82)



### Data Sources

The primary dataset used for this analysis is the "Bitcoin Historical Data.csv" file from **QUANTUM ANALYTICS** contained detailed information about trading Volume by BTC and Currency, including amount open and close with. 

### Tools 

- Power Query - Data Cleaning
- Power BI- Data Analysis
- Power BI - Create Report

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following task:

1. Loading data on Power query
2. Inspection and aligning 
3. Data cleaning and formatting
4. Loading data for Analyzing
5. Create new measures 

### Exploratory Data Analysis

EDA involved exploring the Bitcoin Historical Data to answer key question such as:

- What is the total opening trading value
- What is the total closing trading value
- What is the total high and low value
- What is the total volume BTC and Currency
- What is the total volume both by BTC and currency by month in year
- What is the total weight price by month in years

### Data Analysis

Include some interesting formula worked with

```
 POWER BI
- Sum close = SUM('bitstampUSD_1-min_data_2012-01-01_to_2021-03-31'[Close])

```

### Results/Findings

The analysis results are summarized as follow:
1. That bitcoin is a fluctuating marking 
2. Volume either by BTC or currency those to determine the weight price
3. There is always slight different from the opening value to close value
4. There is tendency that a coin that rice now will fall in next hours
 

### Recommendation

Based on the analysis, we recommend the following actions:
- The market should be carefully studied before investing
- Weight price should be the determinant for investing 


### Limitations

- I had to create new measure for sum close to make the analysis meaningful

### References

Bitcoin charts for the data. The various exchange APIs, for making it difficult or unintuitive enough to 
get OHLC and volume data at 1-min intervals that I set out on this data scraping project. Satoshi 
Nakamoto and the novel core concept of the block chain, as well as its first execution via the bitcoin 
protocol. I'd also like to thank viewers like you! Can't wait to see what code or insights you all have to 
share.
