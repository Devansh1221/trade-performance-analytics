# Trade Performance Analytics Dashboard

An interactive **Options Trading Performance Analytics Dashboard** built using **Python and Microsoft Power BI** to analyze historical trade performance, identify trading patterns, and evaluate profitability across time, instruments, option types, and holding periods.

## Project Overview

This project transforms raw options tradebook data into an interactive analytics dashboard.

The workflow consists of:

**Raw Trade Data → Python Data Cleaning & Feature Engineering → Power BI Data Model → Interactive Trading Analytics**

The analysis covers **785 trades** and focuses on understanding where trading performance has historically been strongest or weakest.

## Tech Stack

* **Python**

  * Pandas
  * NumPy
  * Regular Expressions
* **Microsoft Power BI**
* **DAX**
* **Git & GitHub**

## Key Features

### Performance Analytics

* Total trades
* Net realized P&L
* Win rate
* Average winning trade
* Average losing trade
* Largest winning and losing trades
* Cumulative P&L
* Equity curve

### Time-Based Analysis

* Day-wise performance
* Monthly P&L
* Trading session analysis
* 30-minute time-slot analysis
* Holding-time analysis
* Duration-based performance

### Options Analytics

* Underlying-wise performance
* CE vs PE comparison
* Strike-wise P&L
* Scrip-wise performance
* Quantity vs P&L analysis

### Risk & Behaviour Analysis

* Drawdown analysis
* Winning and losing streaks
* P&L distribution
* Trade ranking
* Trade efficiency based on holding duration

### Edge Discovery

The dashboard combines multiple dimensions such as:

* Trading Day
* Underlying
* Option Type
* Holding Duration

to identify combinations associated with stronger or weaker historical performance.

## 🐍 Python Data Processing

Python was used to transform the raw tradebook into an analytics-ready dataset.

Key transformations include:

* Data type conversion
* Duplicate removal
* Date/time feature extraction
* Holding duration calculation
* Profit percentage calculation
* Trade result classification
* Option underlying extraction
* Expiry and strike extraction
* CE/PE classification
* Cumulative P&L calculation
* Equity curve generation
* Drawdown calculation
* Winning/losing streak calculation
* Trade ranking
* Trade efficiency calculation
* Profit bucket classification

## Data Privacy

The original CSV/Excel trade dataset is **not included in this repository**.

The repository contains the Power BI dashboard and project documentation only.

## Disclaimer

This project is intended for **educational and analytical purposes only**.

Historical trading performance does not guarantee future results, and the analysis should not be interpreted as financial advice or a recommendation to trade.

## Author

**Devansh Mongia**

Mechanical Engineering Undergraduate | Data Analytics | Python | Power BI | SQL
