# Trader Behavior vs Market Sentiment Analysis

## Project Overview
This project analyzes the relationship between trader performance and Bitcoin market sentiment using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index. The objective is to understand how market sentiment influences trader behavior and to derive practical, data-driven trading strategies.

## Datasets Used

### 1. Historical Trader Data (Hyperliquid)
This dataset contains transaction-level trading information, including:
- Execution price  
- Trade size  
- Trade side (buy/sell)  
- Closed profit and loss (PnL)

### 2. Bitcoin Fear & Greed Index
This dataset provides daily Bitcoin market sentiment information, including:
- Sentiment score  
- Sentiment classification (Fear, Extreme Fear, Greed)

## Methodology
- Performed data cleaning and preprocessing to handle timestamps, missing values, and data type inconsistencies.
- Applied feature engineering to create daily performance metrics such as total PnL, trading volume, win rate, and trade count.
- Aggregated trader data at a daily level and merged it with market sentiment data.
- Conducted Exploratory Data Analysis (EDA) to identify behavioral patterns across different sentiment conditions.
- Developed actionable trading strategy recommendations based on observed insights.

## Key Insights
- Trading activity and volume increase significantly during Greed market conditions.
- Profitability during Greed phases is more volatile, indicating higher risk exposure.
- Win rates tend to be higher during Fear and Extreme Fear periods.
- Market sentiment influences trader behavior more strongly than direct profitability.

## Outputs
All visualizations generated during the analysis are stored in the `outputs/` folder, including:
- Profit and Loss vs Market Sentiment
- Trading Volume vs Market Sentiment
- Win Rate vs Market Sentiment
- Trade Count vs Market Sentiment

## How to Run the Project
1. Open `notebook_1.ipynb` in Google Colab.
2. Upload the CSV files from the `csv_files/` folder.
3. Run all cells in sequence.
4. Review the
