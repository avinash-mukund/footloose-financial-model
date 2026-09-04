# Footloose Travel Ltd – Corporate Financial Modeling & Valuation

A corporate finance and financial forecasting project evaluating the post-COVID recovery trajectory for Footloose Travel Ltd (ASX-listed). This repository contains historical ratio performance models, pro-forma financial statement projections (FY2023), capital structure analysis, and capital budgeting (NPV/IRR/PI) for proposed hotel property investments.

---

## Executive Summary

- **Pro-Forma Funding Deficit:** Base-case scenario modeling indicates an **External Funding Required (EFR)** of **$30.37M** to support operational expansion.
- **Capital Budgeting Verdict:** The O'Riordan Investment project demonstrates strong economic viability:
  - **Net Present Value (NPV):** $13.08M
  - **Internal Rate of Return (IRR):** 10.45%
  - **Profitability Index (PI):** 2.01
- **Recommendation:** Proceed with the CapEx deployment financed via a hybrid debt-equity structure to manage liquidity risks.

---

## Historical Ratio Trend Summary (2014–2022)

| Financial Metric | FY2014–FY2019 Trend | FY2020–FY2021 Impact | FY2022 Recovery Status |
| :--- | :--- | :--- | :--- |
| **Return on Equity (ROE)** | Stable baseline (~12–15%) | Severe negative drawdowns | Rebounding toward positive territory |
| **Return on Assets (ROA)** | Steady margin performance | Compressed by low asset turnover | Initial margin recovery |
| **Profit Margin (PM)** | Consistent profitability | Distorted by fixed costs & low volume | Restoring operational efficiency |
| **Liquidity & Leverage** | Balanced debt-to-equity ratio | Liquidity reserves deployed | Capital structure optimization required |

---

## Financial Model Architecture

The pro-forma models and capital budgeting logic are built around three main analytical pillars:

1. **Pro-Forma Financial Statements (FY2023):** Forecasts operating revenues, expenses, balance sheet line items, and computes net External Funding Required (EFR).
2. **Scenario & Sensitivity Analysis:** Evaluates funding volatility across conservative, base-case, and aggressive demand scenarios.
3. **Discounted Cash Flow (DCF) & Investment Appraisal:** Appraises the O'Riordan hotel project over its life cycle using hurdle rates derived from WACC.

---

## Quick Start

```bash
python src/valuation_model.py
