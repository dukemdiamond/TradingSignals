# Trading Signals - SMA & Relative Strength

This Python script performs technical analysis on 13 stocks, calculating Simple Moving Averages (SMA) and Relative Strength (RS) compared to SPY during Q2 2025.

## Stocks Analyzed

**TXN** • **AMAT** • **COUR** • **GNRC** • **IDCC** • **LLY** • **NICE** • **NOK** • **WFC** • **REGN** • **AMD** • **GRAL** • **KLAC**

## Technical Indicators

- **SMA**: 50, 100, 200-day Simple Moving Averages
- **Relative Strength**: `(Stock Price / SPY Price) × 100`

## Key Results - Relative Strength Performance

### Top Performers (RS > 100)
| Stock | Q2 2025 | April | May | June |
|-------|---------|-------|-----|------|
| **LLY** | 137.33 | 148.97 | 129.23 | 129.44 |
| **KLAC** | 127.62 | 122.56 | 129.50 | 135.50 |
| **REGN** | 100.81 | 108.32 | 100.03 | 83.66 |

### Mid-Tier Performers
| Stock | Q2 2025 | April | May | June |
|-------|---------|-------|-----|------|
| **IDCC** | 36.94 | 36.76 | 36.95 | 37.37 |
| **TXN** | 30.39 | 29.09 | 30.75 | 32.36 |
| **NICE** | 28.34 | 28.27 | 28.11 | 29.20 |
| **AMAT** | 27.24 | 26.50 | 27.76 | 27.78 |
| **GNRC** | 21.21 | 21.11 | 21.20 | 21.31 |
| **AMD** | 18.33 | 17.22 | 18.75 | 19.84 |

### Underperformers
| Stock | Q2 2025 | April | May | June |
|-------|---------|-------|-----|------|
| **WFC** | 12.58 | 12.32 | 12.79 | 12.63 |
| **GRAL** | 6.00 | 5.27 | 6.48 | 6.69 |
| **COUR** | 1.44 | 1.34 | 1.51 | 1.50 |
| **NOK** | 0.91 | 0.93 | 0.90 | 0.90 |

## Analysis Highlights

**Strongest Momentum**: AMD (17.22 → 19.84), TXN (29.09 → 32.36)

**Most Consistent**: IDCC (~37 RS), NICE (~28 RS)

**Highest Volatility**: LLY (148.97 → 129.44), REGN (108.32 → 83.66)

## Visualizations

### SMA Analysis
![SMA Charts](https://github.com/user-attachments/assets/c127e1c3-7863-49b6-95d5-427eec8b1f95)

*50, 100, and 200-day moving averages for all 13 stocks*

## Files Generated

- `q2_sma_df.csv`
- `april_sma_df.csv` 
- `may_sma_df.csv`
- `june_sma_df.csv`

## Dependencies

```bash
pip install yfinance pandas alpha-vantage matplotlib
```

## Usage

```python
python stock_analysis.py
```
