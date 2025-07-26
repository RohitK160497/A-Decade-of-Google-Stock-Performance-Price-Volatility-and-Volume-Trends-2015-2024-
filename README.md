# 📈 Google Stock Performance Dashboard (2015–2024)

## 🧠 Project Overview

This project analyzes the daily stock performance of **Alphabet Inc. (GOOGL)** from **2015 to 2024**, focusing on key financial metrics including price trends, daily returns, trading volume, and volatility. Using **Tableau**, we built an interactive dashboard to provide insights into stock behavior over a decade.

## 🎯 Objective

- Identify historical trends in GOOGL stock performance
- Assess volatility, volume fluctuations, and return distributions
- Enable user-driven analysis via interactive filters
- Help investors and analysts make data-informed decisions

---

## 🗃️ Dataset Information

- **Source:** Google Finance (via Kaggle)
- **Ticker:** GOOGL (Class A shares)
- **Frequency:** Daily (Trading Days)
- **Date Range:** Jan 1, 2015 – Dec 31, 2024

### 📊 Data Fields
- Date, Open, High, Low, Close
- Volume
- Derived Metrics:
  - `Daily Return (%) = ((Close - Previous Close) / Previous Close) * 100`
  - `30-Day Moving Average (MA)`
  - `Volatility = High - Low`

---

## 🛠️ Tools Used

- **Tableau Public** (for dashboard creation)
- **Microsoft Excel / Python** (for data preprocessing)
- **Tableau Workbook File:** `Tableau File.twb`

---

## 📈 Dashboard Components

| Component                        | Chart Type       | Description |
|-------------------------------|------------------|-------------|
| **1. Price Trend + 30-Day MA** | Dual Line Chart  | Visualizes raw Close Price and smoothed 30-Day Moving Average |
| **2. Daily Return Histogram**  | Histogram        | Analyzes frequency of daily return rates to understand risk distribution |
| **3. Avg. Close Price by Month** | Line Chart     | Shows monthly price evolution for trend identification |
| **4. Total Volume by Month**   | Bar Chart        | Tracks trading activity intensity |
| **5. Average Monthly Volatility** | Line Chart    | Measures market uncertainty across time |
| **6. Volatility Over Time**    | Line Chart        | Shows annual shifts in volatility levels |

---

## 📌 Key Findings

- GOOGL stock showed **strong upward momentum**, with significant growth in 2021 and 2024.
- The **30-Day Moving Average** effectively highlighted long-term trends and mitigated short-term noise.
- **Daily return distribution** is centered near 0%, with rare extreme values (fat-tailed).
- **Volume spikes** aligned with high-volatility periods and major tech announcements.
- **Volatility peaked** in 2020 (COVID-19) and late 2023, reflecting market shocks.

---

## 💡 Recommendations

- Monitor **moving average crossovers** for identifying bullish/bearish shifts.
- Combine **volume + volatility** to anticipate breakouts or breakdowns.
- Consider **earnings cycles and macro events** when evaluating price trends.
- For risk-aware investing, analyze **return distributions** to understand historical variability.

---

## 📁 Repository Structure

