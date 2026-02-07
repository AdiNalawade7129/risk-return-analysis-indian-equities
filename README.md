# Risk–Return Analysis of Indian Equities Relative to the NIFTY 50

## 📌 Project Overview
This project analyzes the long-term performance of selected Indian equities relative to the NIFTY 50 benchmark using quantitative risk and return metrics. Rather than focusing solely on absolute returns, the analysis emphasizes the quality, stability, and sustainability of returns over time.

The project demonstrates how data-driven methods can support more informed, risk-aware investment and managerial decision-making.

---

## 🎯 Project Objective
The objective of this project is to evaluate the long-term performance of selected Indian equities relative to the NIFTY 50 benchmark using return, risk, and downside metrics. The analysis aims to assess not only absolute wealth creation through compounding, but also the quality of returns by examining volatility and maximum drawdowns.

---

## 📊 Data Description
- **Source:** Yahoo Finance (via `yfinance` Python library)
- **Time Period:** 2010 – 2024
- **Assets Analyzed:**
  - TCS
  - HDFC Bank
  - ITC
  - Infosys
  - Reliance Industries
  - Larsen & Toubro
  - NIFTY 50 (Benchmark)

Daily closing price data was used for all calculations.

---

## 🧮 Methodology
The analysis follows a structured, multi-step approach:

1. **Data Collection**
   - Historical price data was programmatically collected using Python to ensure reproducibility.

2. **Data Normalization**
   - Prices were normalized to simulate the growth of ₹100 invested in each asset, enabling fair visual comparison.

3. **Return Analysis**
   - Compound Annual Growth Rate (CAGR) was calculated to measure long-term compounding performance.

4. **Risk Analysis**
   - Annualized volatility was computed using daily returns to assess price fluctuations.

5. **Downside Risk**
   - Maximum drawdown was calculated to evaluate the worst peak-to-trough loss experienced by each asset.

6. **Risk-Adjusted Performance**
   - A simplified Sharpe-like ratio (CAGR / Volatility) was used to assess return efficiency relative to risk.

---

## 📈 Key Insights
- **TCS** demonstrated the strongest overall performance, combining the highest long-term compounding with comparatively lower volatility and the smallest maximum drawdown.
- **HDFC Bank** delivered strong returns with moderate volatility but experienced deeper drawdowns during periods of market stress.
- **ITC**, despite reasonable long-term returns, showed significant downside risk, highlighting the importance of considering drawdowns alongside returns.
- The **NIFTY 50** benchmark exhibited lower volatility due to diversification but delivered lower long-term returns compared to select high-quality stocks.

These results indicate that high-quality businesses can generate superior long-term returns while simultaneously limiting downside risk.

---

## ⚠️ Limitations
- The analysis is based solely on historical price data.
- Valuation metrics, macroeconomic factors, and company fundamentals are not considered.
- Past performance does not guarantee future results.

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- yfinance
- Jupyter Notebook (VS Code)

---

## 📌 Conclusion
This project illustrates the importance of evaluating investments through a multi-dimensional lens that includes returns, risk, and downside exposure. Such an approach is applicable not only to equity investing but also to broader business and managerial decision-making contexts.

