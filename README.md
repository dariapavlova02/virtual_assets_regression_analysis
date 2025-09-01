# Virtual Assets Regression Analysis

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

## 📊 About

This project analyzes the relationship between Bitcoin (BTC) and MicroStrategy (MSTR) stock prices using regression analysis. The analysis explores how virtual assets (cryptocurrencies) influence traditional financial instruments and provides insights into portfolio diversification strategies.

## 🎯 Objectives

- Analyze the correlation between BTC and MSTR prices
- Perform linear regression analysis to quantify the relationship
- Calculate key statistical metrics (R², correlation coefficient, beta)
- Model scenarios for different cryptocurrency allocation strategies
- Provide insights for investment decision-making

## 📈 Key Findings

### Statistical Results
- **Correlation Coefficient**: 0.8649 (86.49%)
- **R-squared (R²)**: 0.7481 (74.81%)
- **Beta Coefficient**: 0.0029
- **Intercept**: -41.9911

### Virtual Assets Analysis
- MicroStrategy's virtual assets represent **92.52%** of total assets
- Strong positive correlation between BTC and MSTR performance
- High explanatory power of the regression model

## 🛠️ Technologies Used

- **Python 3.7+**
- **Jupyter Notebook**
- **yfinance** - Financial data retrieval
- **pandas** - Data manipulation and analysis
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization
- **scikit-learn** - Machine learning algorithms

## 📋 Prerequisites

- Python 3.7 or higher
- pip package manager
- Jupyter Notebook or JupyterLab

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/dariapavlova02/virtual_assets_regression_analysis.git
   cd virtual_assets_regression_analysis
   ```

2. **Install dependencies**
   ```bash
   pip install yfinance pandas matplotlib seaborn scikit-learn jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open `analysis.ipynb`**

## 📊 Usage

1. **Data Collection**: The notebook automatically downloads BTC and MSTR price data from Yahoo Finance
2. **Data Processing**: Combines and cleans the datasets
3. **Visualization**: Creates charts showing price movements and relationships
4. **Regression Analysis**: Performs linear regression and calculates key metrics
5. **Scenario Modeling**: Models different cryptocurrency allocation strategies

## 📁 Project Structure

```
virtual_assets_regression_analysis/
├── analysis.ipynb          # Main analysis notebook
├── README.md               # Project documentation
└── LICENSE                 # Apache 2.0 license
```

## 🔍 Analysis Components

### 1. Data Collection
- BTC-USD price data (2020-2025)
- MSTR stock price data (2020-2025)

### 2. Statistical Analysis
- Linear regression model
- Correlation analysis
- R-squared calculation
- Beta coefficient estimation

### 3. Visualization
- Price movement charts
- Regression plots
- Scenario modeling graphs

### 4. Scenario Modeling
- Different BTC allocation percentages (5%, 10%, 15%, 20%, 25%)
- Adjusted R² and correlation coefficients for Monobank scenarios

## 📊 Results Interpretation

### High Correlation (0.8649)
- Strong positive relationship between BTC and MSTR
- Suggests MSTR stock is heavily influenced by Bitcoin performance

### High R-squared (0.7481)
- 74.81% of MSTR price variation explained by BTC price
- Model has strong predictive power

### Beta Coefficient (0.0029)
- For every $1 increase in BTC, MSTR increases by $0.0029
- Indicates moderate sensitivity to BTC price changes

## 🎯 Investment Implications

- **Portfolio Diversification**: High correlation suggests limited diversification benefits
- **Risk Management**: BTC volatility directly impacts MSTR stock risk
- **Strategic Allocation**: Consider correlation when building crypto-exposed portfolios

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Daria Pavlova** - [@dariapavlova02](https://github.com/dariapavlova02)

## 📞 Contact

- GitHub: [@dariapavlova02](https://github.com/dariapavlova02)
- Repository: [virtual_assets_regression_analysis](https://github.com/dariapavlova02/virtual_assets_regression_analysis)
