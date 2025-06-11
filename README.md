# MAANG Stock Market Analysis (2015-2024)

## 📊 Project Overview

This project presents a comprehensive 10-year financial analysis of major technology companies collectively known as MAANG (META, AAPL, AMZN, NFLX, GOOG). Using Python and various data analysis libraries, this study examines stock performance, trading patterns, and investment potential from 2015 to 2024.

## 🎯 Objectives

- Analyze long-term stock performance trends across MAANG companies
- Identify momentum indicators and price patterns using technical analysis
- Evaluate investment returns and volatility across different time horizons
- Compare dividend policies and income generation potential
- Provide data-driven insights for investment decision-making

## 🛠️ Technologies & Tools

- **Python 3.x** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **yFinance** - Yahoo Finance API for stock data retrieval
- **Matplotlib** - Data visualization and plotting
- **Seaborn** - Statistical data visualization

## 📈 Companies Analyzed

| Symbol | Company | Industry Focus |
|--------|---------|---------------|
| META | Meta Platforms Inc. | Social Media & VR |
| AAPL | Apple Inc. | Consumer Electronics |
| AMZN | Amazon.com Inc. | E-commerce & Cloud |
| NFLX | Netflix Inc. | Streaming Entertainment |
| GOOG | Alphabet Inc. | Search & Cloud Services |

## 🔍 Analysis Components

### 1. Data Collection & Processing
- Historical stock data retrieval using yFinance API
- Data cleaning and validation
- Time-series resampling (daily, weekly, yearly aggregations)

### 2. Technical Analysis
- **Moving Averages**: 20-day and 50-day moving averages
- **Price Trends**: Closing price analysis and trend identification
- **Volume Analysis**: Trading volume patterns and liquidity assessment
- **Volatility Metrics**: Stock price volatility comparisons

### 3. Performance Metrics
- **Returns Analysis**: 
  - Weekly returns calculation and visualization
  - Yearly percentage returns
  - Cumulative 10-year total returns
- **Risk Assessment**: Volatility analysis and risk-return profiles

### 4. Dividend Analysis
- Historical dividend payout tracking
- Dividend yield comparisons
- Income generation potential evaluation
- Shareholder value assessment

### 5. Comparative Analysis
- Cross-company performance benchmarking
- Sector-wide trend identification
- Investment opportunity ranking

## 📋 Key Features

- **Automated Data Retrieval**: Seamless integration with Yahoo Finance API
- **Interactive Visualizations**: Comprehensive charts and graphs using Matplotlib/Seaborn
- **Multi-timeframe Analysis**: Daily, weekly, and yearly data perspectives
- **Risk-Return Metrics**: Comprehensive performance evaluation
- **Dividend Tracking**: Income-focused investment analysis

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy yfinance matplotlib seaborn
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/prasad-hp/stock_market-ny.git
cd maang-stock-analysis
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the analysis:
```bash
python main.py
```

## 📊 Sample Visualizations

The project generates various types of visualizations including:

- Historical closing price trends
- Moving average overlays
- Volume trading patterns
- Weekly/yearly return distributions
- Comparative performance charts
- Dividend payout timelines
- Volatility comparison matrices



## 🔄 Future Enhancements

- [ ] Real-time data integration
- [ ] Advanced technical indicators (RSI, MACD, Bollinger Bands)
- [ ] Machine learning price prediction models
- [ ] Interactive dashboard development
- [ ] Portfolio optimization algorithms
- [ ] Sector rotation analysis

## 📝 Usage Examples

```python
# Example: Fetch and analyze AAPL data
from src.data_collector import get_stock_data
from src.analyzer import calculate_returns

# Get Apple stock data
aapl_data = get_stock_data('AAPL', '2015-01-01', '2024-12-31')

# Calculate returns
weekly_returns = calculate_returns(aapl_data, period='weekly')
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## ⚠️ Disclaimer

This analysis is for educational and informational purposes only. It should not be considered as financial advice. Always consult with a qualified financial advisor before making investment decisions.

## 📞 Contact

Your Name - [itsprasadhp@gmail.com](mailto:itsprasadhp@gmail.com)

Project Link: https://github.com/prasad-hp/stock_market-ny

## 🙏 Acknowledgments

- Yahoo Finance for providing free stock market data
- The Python community for excellent data analysis libraries
---

⭐ **If you found this project helpful, please consider giving it a star!** ⭐
