# Gold (XAUUSD) Quantitative Market Analysis (2021–2025)

This project is a complete quantitative analysis of **Gold Futures (GC=F / XAUUSD)** using Python.  
The goal of this analysis is to study gold price behavior, volatility, risk metrics, momentum indicators, and correlations with other major financial assets between **2021 and 2025**.

The project produces multiple professional charts and a final market summary report that can be used for trading research, portfolio analysis, and quantitative finance learning.

---

## Project Objectives

- Analyze long-term price trend of Gold (2021–2025)
- Identify bullish/bearish trends using moving averages
- Measure volatility and risk using rolling volatility and drawdowns
- Evaluate performance using CAGR and Sharpe Ratio
- Detect swing highs/lows for key support & resistance zones
- Study seasonality patterns (monthly return behavior)
- Compare Gold correlation with major assets like S&P500, USD Index, Oil, Bitcoin, and Silver

---

## Key Features

### Price & Trend Analysis
- Gold price trend chart (2021–2025)
- 50-day and 200-day Moving Averages (MA50, MA200)
- Trend classification:
  - Bullish (MA50 > MA200)
  - Bearish (MA50 < MA200)
  - Sideways (equal / neutral)

### Technical Indicators
- RSI (14) indicator with overbought/oversold zones
- Candlestick chart visualization using mplfinance

### Risk & Performance Metrics
- Daily returns calculation
- Monthly seasonality analysis
- Yearly volatility analysis
- 30-day rolling volatility
- Drawdown analysis (max drawdown and drawdown periods)
- CAGR (Compound Annual Growth Rate)
- Sharpe Ratio and 90-day rolling Sharpe Ratio chart

### Support & Resistance Levels
- Swing high / swing low detection
- Identification of most repeated key price levels
- Candlestick chart with key support/resistance overlays

### Multi-Asset Correlation
- Correlation analysis of Gold with:
  - S&P 500 (SPY)
  - USD Index (DX-Y.NYB)
  - Oil (CL=F)
  - Bitcoin (BTC-USD)
  - Silver (SI=F)
- Correlation heatmap visualization

---

## Tools & Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **yFinance**
- **mplfinance**

---

## Data Source

All historical market data is fetched using the **yFinance API** from Yahoo Finance.

- Gold Futures: `GC=F`
- Other assets: SPY, DX-Y.NYB, CL=F, BTC-USD, SI=F

---

## Project Workflow

1. Download Gold Futures data (2021–2025)
2. Clean dataset and compute daily returns
3. Generate trend and moving average charts
4. Perform seasonality and volatility analysis
5. Compute RSI and rolling volatility
6. Compute drawdown and risk metrics
7. Calculate CAGR and Sharpe Ratio
8. Detect swing highs/lows and key price zones
9. Perform multi-asset correlation study
10. Generate correlation heatmap
11. Print final professional summary report

---

## Output Visualizations

This project generates:
- Gold price trend chart
- Moving averages chart
- Monthly seasonality bar chart
- Yearly volatility bar chart
- Candlestick charts
- RSI chart
- Rolling volatility chart
- Drawdown chart
- Rolling Sharpe ratio chart
- Return distribution histogram
- Swing high/low chart
- Correlation heatmap

---

## How to Run the Project

### 1. Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn yfinance mplfinance
