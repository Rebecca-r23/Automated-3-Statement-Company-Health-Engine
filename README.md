# Automated 3-Statement Company Health Engine

A dynamic financial modeling tool that integrates the three core financial statements to automate company valuation and performance forecasting.

## 🚀 Overview

This project provides a robust framework for financial analysis. By inputting a few key drivers, the model automatically generates a 5-year projection, balances the Balance Sheet, and calculates the intrinsic value of a business using a Discounted Cash Flow (DCF) approach.

## 📊 Model Structure

The engine is divided into several interconnected modules:

* **Inputs/Assumptions:** The control center where users define Revenue Growth, Margins, Tax Rates, and WACC.
* **Income Statement:** Projects profitability from Revenue down to Net Income.
* **Balance Sheet:** Tracks Assets, Liabilities, and Equity, ensuring $Assets = Liabilities + Equity$.
* **Cash Flow Statement:** Reconciles Net Income to Cash, providing a clear view of Operating, Investing, and Financing activities.
* **Debt Engine:** Manages debt schedules and calculates interest impact.
* **Valuation:** Determines Enterprise Value (EV) and provides market multiples ($EV/EBITDA, P/E$).
* **Executive Dashboard:** High-level summary of the company's financial trajectory.

## 🛠️ Key Features

* **Circular Logic Management:** Handles the relationship between debt, interest, and cash flow.
* **Automated DCF:** Built-in calculation for Terminal Value and Present Value of Free Cash Flows.
* **Health Metrics:** Automatic calculation of working capital requirements and capital expenditure impacts.
* **Sensitivity Ready:** Designed to allow rapid scenario testing by adjusting core assumptions.

## 📈 Financial Ratios Included

* **Profitability:** Gross Margin, EBITDA Margin, Net Margin.
* **Valuation:** Enterprise Value, $P/E$ Ratio, $EV/EBITDA$.
* **Efficiency:** Working Capital % of Revenue.

## 💻 How to Use

1.  **Data Entry:** Enter historical data (Year 0) in the respective statement sheets.
2.  **Set Assumptions:** Update the `Inputs` sheet with expected growth rates and cost structures.
3.  **Analyze:** View the `Valuation` sheet for the calculated company value.
4.  **Review:** Use the `Dashboard` for a visual representation of the company's health.

---
*Disclaimer: This model is for educational and analytical purposes only and does not constitute financial advice.*
