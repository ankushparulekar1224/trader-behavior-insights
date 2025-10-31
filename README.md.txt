# Trader Behavior Insights – Bitcoin Sentiment Analysis

## 📊 Project Overview

This project analyzes the relationship between **Bitcoin market sentiment** (Fear & Greed Index) and **trader performance** on Hyperliquid. The analysis explores how market psychology influences trading outcomes, leverage usage, and profitability patterns.

## 🎯 Objectives

- Understand how Fear/Greed sentiment impacts trader win rates and PnL
- Identify leverage patterns during different sentiment periods
- Build a predictive model for profitable trades
- Extract actionable insights for traders and analysts

## 📁 Project Structure

```
trader-behavior-insights/
├── data/
│   ├── hyperliquid_trades.csv      # Trading data from Hyperliquid
│   └── fear_greed.csv              # Bitcoin Fear & Greed Index
├── notebooks/
│   └── trader_behavior_analysis.ipynb  # Main analysis notebook
├── reports/
│   └── summary.md                  # Key findings and insights
├── requirements.txt                # Python dependencies
└── README.md                       # This file
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone or download this repository**

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the datasets:**
   - Place `hyperliquid_trades.csv` in the `data/` folder
   - Place `fear_greed.csv` in the `data/` folder

### Running the Analysis

1. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. **Open the notebook:**
   - Navigate to `notebooks/trader_behavior_analysis.ipynb`

3. **Run all cells:**
   - Click `Cell → Run All` or run cells sequentially

## 📈 Analysis Components

### 1. Data Loading & Cleaning
- Loads trading and sentiment data
- Handles missing values and date parsing
- Merges datasets by trade date

### 2. Feature Engineering
- Converts sentiment classifications to numeric scores
- Calculates notional trade values
- Creates win/loss indicators

### 3. Exploratory Data Analysis
- Daily PnL vs. sentiment visualization
- Win rate comparison across sentiment periods
- Correlation analysis of key features

### 4. Predictive Modeling
- Logistic regression to predict profitable trades
- Feature importance analysis
- Model evaluation and metrics

### 5. Key Insights
- Comprehensive summary of findings
- Actionable recommendations for traders

## 📊 Key Features

- **Sentiment Score Mapping:** Fear = -1, Neutral = 0, Greed = +1
- **Win Rate Analysis:** Percentage of profitable trades by sentiment
- **Leverage Patterns:** Average leverage usage during Fear vs. Greed
- **Feature Correlations:** Relationships between sentiment, leverage, and PnL

## 🛠️ Technologies Used

- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computations
- **matplotlib & seaborn** - Data visualization
- **scikit-learn** - Machine learning and modeling
- **statsmodels** - Statistical analysis

## 📝 Results

Results are saved in:
- **Notebook:** All visualizations and intermediate outputs
- **Reports:** `reports/summary.md` contains a concise summary of findings

## 🤝 Contributing

This is a demonstration project for data science portfolio purposes. Feel free to fork and adapt for your own analysis.

## 📧 Contact

For questions or feedback about this analysis, please refer to the insights in `reports/summary.md`.

## 📄 License

This project is for educational and portfolio demonstration purposes.

---

**Note:** Ensure all data files are properly placed in the `data/` directory before running the notebook.