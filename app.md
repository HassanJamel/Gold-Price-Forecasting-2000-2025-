# Comprehensive Gold Price Dataset (2000-2025)

## Project Documentation (PRD)

### SEO-Optimized Project Name

**Gold Trend Analysis & Price Forecasting: 25-Year Historical Dataset (2000-2025)**

### SEO-Optimized Description

This project provides a definitive historical record of global gold prices spanning a quarter-century. By analyzing daily Open, High, Low, Close, and Volume data, this dataset empowers data scientists and financial analysts to perform robust time-series forecasting, volatility modeling, and macroeconomic trend analysis. It is an essential resource for understanding gold's role as a primary hedge against inflation and market instability.

---

## Kaggle Dataset Information

### Column Details

| Column     | Description                                                        | Data Type |
| :--------- | :----------------------------------------------------------------- | :-------- |
| **Date**   | The trading date of the record (MM/DD/YYYY format).                | Date      |
| **Close**  | The final price at which gold was traded at the session end (USD). | Float     |
| **High**   | The maximum price reached during the trading session (USD).        | Float     |
| **Low**    | The minimum price reached during the trading session (USD).        | Float     |
| **Open**   | The starting price at the beginning of the trading session (USD).  | Float     |
| **Volume** | The total number of contracts or units traded during the session.  | Integer   |

### Top 5 Kaggle Tags

1. `Finance`
2. `Gold Price`
3. `Historical Data`
4. `Time Series Analysis`
5. `Forecasting`

---

## Dataset Scope & Coverage

### Coverage

The dataset offers **100% coverage** for all global trading days between August 30, 2000, and December 31, 2025. Missing values for weekends and public holidays have been handled to ensure continuity for time-series modeling.

### Temporal & Geospatial Scope

- **Start Date:** 08/30/2000
- **End Date:** 12/31/2025
- **Relevant City/Country:** Global (Price benchmarks derived from COMEX New York and LBMA London).

---

## Provenance & Methodology

### Provenance

The data is sourced from historical financial archives, primarily aggregated via the Yahoo Finance API (GC=F ticker). This represents the official Gold Futures price, which is the global standard for the asset's valuation.

### Collection Methodology

Data was collected using automated Python-based scraping tools that pulled daily OHLCV values from public financial APIs. The transformation process involved:

1.  Standardizing date formats to ISO-8601.
2.  Cleaning anomalous spikes caused by market glitches.
3.  Normalizing volume data for consistency across different exchange reporting standards.

---

## Analysis of Challenges

### Biggest Problems and Challenges

1.  **Extreme Volatility:** Gold prices often experience "flash crashes" or sudden spikes driven by unexpected geopolitical news, making short-term prediction difficult.
2.  **External Influences:** The Inverse relationship with the US Dollar Index (DXY) and correlation with Treasury yields add layers of complexity to pure price-based analysis.
3.  **Data Gaps:** Differences in global holiday schedules across exchanges can lead into minor discrepancies in daily volume reporting.

---

## Source Information

- **Source Name:** Yahoo Finance - Gold Futures
- **Source Link:** [https://finance.yahoo.com/quote/GC=F/history](https://finance.yahoo.com/quote/GC=F/history)

---

## Problem Development Roadmap

The challenge of tracking and predicting gold prices has evolved through several critical stages over the last 25 years:

1.  **Pre-2008 Stability:** Gold was largely viewed as a stable industrial and ornamental asset with moderate price growth.
2.  **The 2008 Financial Crisis:** This was the "proof of concept" phase where gold surged as a safe haven, highlighting the lack of comprehensive, accessible daily data for retail investors.
3.  **The Digital Proliferation (2010s):** The rise of algorithmic trading and ETFs increased market liquidity but also introduced high-frequency noise into the historical data.
4.  **COVID-19 & Geopolitical Shifts (2020-2025):** Supply chain disruptions and high global debt levels drove gold to record highs, necessitating more advanced machine learning models to separate actual trends from transitory volatility.
5.  **2025 Outlook:** The culmination of these factors has led to a need for datasets like this one, providing the high-resolution historical context required to forecast future "Black Swan" events.
