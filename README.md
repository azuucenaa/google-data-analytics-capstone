# Financial Market Analysis
## Nasdaq-100 vs S&P 500 | 2016–2025

Comparative analysis of the historical performance and risk of the Nasdaq-100 and S&P 500 between 2016 and 2025, developed in Power BI and supported by Excel-based data preparation and analysis.

![Financial Market Analysis Dashboard](./capturas%20de%20pantalla/dashboard-overview.png)

## Business Question

Did the higher historical return of the Nasdaq-100 between 2016 and 2025 come with a significantly higher level of risk compared with the S&P 500?

## Objective

Analyze the historical performance and risk of both indices using common trading dates and comparable metrics.

The analysis focuses on:

- Cumulative return
- Daily average return
- Daily volatility
- Maximum daily gain and loss
- Maximum Drawdown
- Correlation between daily returns
- Normalized performance from a common base of 100

## Data

The analysis uses historical market data obtained from Yahoo Finance for:

- Nasdaq-100
- S&P 500

The common analysis period covers trading dates from April 4, 2016 to December 30, 2025.

Daily observations were synchronized using common dates before calculating the comparative metrics.

## Methodology

The analysis followed these main steps:

1. Prepare and synchronize the historical market data.
2. Order observations chronologically.
3. Calculate daily returns.
4. Calculate cumulative returns.
5. Calculate cumulative peaks and drawdowns.
6. Calculate Maximum Drawdown.
7. Calculate daily volatility.
8. Calculate the correlation between daily returns.
9. Normalize both indices to a common base of 100.
10. Visualize and compare the results in Power BI.

## Key Metrics

| Metric | Nasdaq-100 | S&P 500 |
|---|---:|---:|
| Average daily return | 0.08% | 0.06% |
| Maximum daily return | 12.02% | 9.52% |
| Minimum daily return | -12.19% | -11.98% |
| Daily volatility | 1.42% | 1.14% |
| Cumulative return | 466.10% | 242.64% |
| Maximum Drawdown | -35.56% | -33.92% |
| Daily return correlation | 0.9346 | — |

## Performance Analysis

The Nasdaq-100 achieved a higher cumulative return during the analyzed period.

The normalized performance comparison also shows that the Nasdaq-100 remained above the S&P 500 throughout most of the period and finished with a substantially higher cumulative growth level.

![Performance Analysis](./capturas%20de%20pantalla/performance-analysis.png)

## Risk Analysis

The Nasdaq-100 presented higher daily volatility than the S&P 500, with 1.42% compared with 1.14%.

Its Maximum Drawdown was also slightly deeper at -35.56%, compared with -33.92% for the S&P 500.

![Risk Analysis](./capturas%20de%20pantalla/risk-analysis.png)

## Correlation

The correlation between the daily returns of both indices was 0.9346, indicating that their daily movements were highly related during the analyzed period.

![Financial Market Analysis Dashboard](./capturas%20de%20pantalla/dashboard-overview.png)

## Key Findings

- The Nasdaq-100 generated a cumulative return of 466.10%, compared with 242.64% for the S&P 500.
- The Nasdaq-100 showed higher daily volatility: 1.42% versus 1.14%.
- The Nasdaq-100 experienced a slightly deeper Maximum Drawdown: -35.56% versus -33.92%.
- The maximum daily gain was higher for the Nasdaq-100, at 12.02% versus 9.52%.
- The minimum daily return was -12.19% for the Nasdaq-100 and -11.98% for the S&P 500.
- Daily returns showed a high correlation of 0.9346.

## Conclusion

The results indicate that the Nasdaq-100 achieved substantially higher historical performance than the S&P 500 during the analyzed period, but this higher return was accompanied by moderately higher volatility and a slightly deeper Maximum Drawdown.

Therefore, the analysis supports the conclusion that the Nasdaq-100's higher historical return was associated with a higher, although not dramatically higher, level of observed risk during the period analyzed.

This project describes historical market behavior and does not constitute personalized investment advice.

## Limitations

The analysis describes historical index behavior and does not incorporate:

- Dividends
- Commissions
- Taxes
- Risk-free rate
- Personalized investment objectives

The return/volatility ratio presented in the analysis should not be interpreted as a Sharpe ratio.

## Tools

- Power BI
- Microsoft Excel
- Data analysis
- Financial performance analysis
- Data visualization

## Project Files

- [Power BI Dashboard](./Power%20BI/financial-market-analysis.pbix)
- [Presentation](./presentación/financial-market-analysis.pdf)
- [Case Study](./documentación/financial-market-analysis-case-study.pdf)
- [Excel Analysis File](./data/capstone-financial-analysis.xlsx)

## Methodology & Documentation

![Methodology and Metrics](./capturas%20de%20pantalla/methodology-metrics.png)
