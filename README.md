# Market Sentiment Analysis

## Overview
This project analyzes market sentiment data (Fear and Greed Index) and transactional data to uncover insights into how market sentiment influences trading behavior.

## Dataset Details
1. **Fear and Greed Index Dataset**:
   - Source: Contains historical market sentiment data.
   - Columns: `timestamp`, `value`, `classification`, `date`.

2. **Historical Trading Data**:
   - Source: Contains transactional data with execution prices, token sizes, and timestamps.

## Steps Performed
1. Data Loading and Inspection.
2. Cleaning and Preprocessing:
   - Converted timestamps to readable formats.
   - Removed duplicates and unnecessary columns.
   - Sorted data for analysis.
3. Exploratory Data Analysis:
   - Trend analysis for the Fear and Greed Index.
   - Distribution plots for execution prices.
   - Correlation analysis.
4. Combined Analysis:
   - Merged datasets on timestamps.
   - Studied relationships between market sentiment and transactional behavior.

## Insights
1. **Market Sentiment Trends**:
   - Fear and Greed Index fluctuates significantly, correlating with major trading events.
2. **Execution Price Behavior**:
   - Execution prices show volatility during "Extreme Fear" periods.
3. **Impact of Sentiment**:
   - Higher trading volume during "Extreme Greed."
   - Smaller transaction sizes during "Fear" periods.
4. **Correlation**:
   - Market sentiment impacts trading strategies, with higher fees during periods of "Greed."

## Technologies Used
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Harry-17/Market-Sentiment-Analysis.git
