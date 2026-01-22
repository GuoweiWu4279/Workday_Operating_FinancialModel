# Workday 3-Statement Operating Model (2020–2024)

This project presents a dynamic, driver-based 3-statement operating model for Workday Inc., built in Excel using historical financial statements and forward-looking assumptions.

The model upgrades simple historical trending to a logic-based forecast, focusing on **ARR (Annual Recurring Revenue) dynamics**, **Operating Leverage**, and **Cash Flow generation** under different scenarios.

---

## 📌 Model Objective

- **Forecast Revenue Quality:** Utilizing an ARR Waterfall structure (Bookings & Churn) rather than simple growth rates.
- **Analyze Operating Leverage:** Assess how R&D and S&M expenses scale relative to revenue under Bear, Base, and Bull scenarios.
- **Cash Flow Divergence:** Evaluate the disconnect between GAAP Net Losses and strong Operating Cash Flow (driven by SBC and Deferred Revenue).
- **Balance Sheet Health:** Project liquidity and capital structure sustainability without external financing.

---

## 🔑 Key Takeaways

- **Revenue Growth:** Revenue grows at ~18% CAGR (from $4.3B to ~$7.1B), driven by strong subscription bookings and low churn assumptions.
- **Profitability Profile:** While GAAP Operating Income (EBIT) remains negative due to high R&D and Stock-Based Compensation (SBC), the model shows potential for operating leverage in outer years.
- **Cash Flow Strength:** Despite accounting losses, **Operating Cash Flow is highly positive** (growing to ~$1.7B+), largely driven by non-cash add-backs (SBC) and upfront deferred revenue collections.
- **Liquidity:** Unlike typical loss-making firms, Workday accumulates significant cash reserves (~$5B by 2024) purely through operations, requiring no new debt or equity financing.

---

## 🏗️ Model Structure

The Excel model includes the following integrated tabs:

- **Summary** – Executive dashboard with key charts and scenario outputs.
- **Assumptions** – **Scenario Toggles (Bear/Base/Bull)** and driver-based inputs for margins and efficiency.
- **Revenue Build** – **ARR Waterfall** modeling (Beginning ARR + New Bookings - Churn = Ending ARR).
- **Financial Statements** – Fully linked 3-Statement view:
  - *Income Statement:* Driver-based operating forecast.
  - *Balance Sheet:* Linked PP&E, Working Capital, and Equity roll-forwards.
  - *Cash Flow Statement:* Derived indirect method cash flow.

---

## ⚙️ Key Assumptions (Base Case)

- **Revenue Model:** ARR-driven approach with ~20% New Bookings growth and ~5% Churn.
- **Cost Structure:** Operating expenses modeled as % of Revenue, with varying efficiency gains per scenario.
- **Taxation:** Zero effective tax rate assumed during loss-making period (utilizing NOLs).
- **Working Capital:** DSO ~88 days; Deferred Revenue maintained at ~55% of ARR.
- **Capex:** Set at ~5-8% of Revenue to sustain infrastructure growth.

---

## 🚫 Model Scope & Limitations

This model intentionally excludes:
- Complex treasury and marketable securities activity.
- Granular headcount planning (bottom-up).
- M&A transactions or capital structure changes.
- Valuation analysis (DCF or Trading Multiples).

The model is designed as an **FP&A / Operating Analysis tool**, focusing on business drivers rather than valuation.

---

## 📂 Files

- `WDAY_Operating_Model.xlsm` – Main model file (Macro-enabled for scenario toggles)

---

## 👤 Author

Built by **Guowei (Gary) Wu** as part of a personal financial modeling and SaaS company analysis project.