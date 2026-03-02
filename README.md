#  Real Estate Treasury & Risk Analysis Dashboard

##  Project Overview

This project presents an end-to-end financial analysis of a synthetic real-estate company using Power BI.

The objective was to simulate a real treasury and financial monitoring scenario, focusing on:

- Cash flow evolution
- Income vs expense structure
- Tenant payment reliability
- Operational sustainability

The dashboard set is designed to mimic real CFO / Treasury reporting and business decision workflows.


##  Business Questions Addressed

### 1 Treasury Health
- How is liquidity evolving over time?
- Is the company generating or consuming cash?

### 2 Cash Flow Drivers
- Which categories drive incoming vs outgoing cash?
- Where is money leaking?

### 3 Tenant Risk Analysis
- Which tenants represent payment risk?
- How concentrated is payment reliability risk?

### 4 Expense Structure
- Are operating costs sustainable?
- What expense categories dominate the cost base?

---

##  Dashboard Structure

###  Dashboard 1 — Treasury Overview
**Purpose:** Executive snapshot of financial health.

Main components:
- Cash Position KPI
- Total Inflows / Outflows
- Net Cash Flow
- Cash balance trend over time
- Inflow vs Outflow comparison
- Top counterparties



###  Dashboard 2 — Cash Flow Drivers
**Purpose:** Understand category-level drivers of cash movement.

Includes:
- Waterfall cash bridge
- Top income categories
- Top expense categories
- Transaction detail table for drilldown



###  Dashboard 3 — Tenant Payment Risk Analysis
**Purpose:** Evaluate tenant payment reliability and risk.

Key metrics:
- OTP (On-Time Payment %)
- Amount at risk
- Risk segmentation (High / Medium / Safe)

Visuals:
- Scatter plot (OTP vs Average Payment)
- Risk table with conditional formatting
- Tenant risk KPIs



###  Dashboard 4 — Expense Structure Overview
**Purpose:** Analyze operational sustainability.

Key KPIs:
- Total OPEX
- OPEX as % of Revenue
- Operating Margin
- Top Expense Driver insight

---

## Key Business Insights

###  Cash Situation
- Cash balance shows continuous decline over the observed period.
- In 2024 alone, net cash flow reached **−0.75M€**, indicating structural cash consumption.

---

###  Tenant Risk Exposure
- 148 active tenants during the selected period.
- 38 tenants (25.7%) classified as **high risk** (OTP < 30%).
- 22 tenants made no payments during the year.
- Only ~11% can be considered safe tenants.

 Revenue reliability is highly unstable.

---

###  Operational Cost Problem
- OPEX represents approximately **127% of revenue**.
- Operating margin remains negative.

This indicates that the current operating model is not financially sustainable.

---

###  Payroll Concentration
- Salaries account for approximately **42% of total OPEX**, making it the largest expense driver.

Possible implication:
- Overextended operational structure or excessive fixed costs.

---

###  Investment vs Operations
- CAPEX exists but remains relatively low compared to operational spending.

This may suggest:
- Limited growth investment while maintaining high recurring costs.

---

##  Strategic Interpretation

The company appears to face a dual risk:

1. **Unstable inflows**
   - High proportion of risky tenants.
   - Weak payment reliability.

2. **Heavy fixed cost structure**
   - OPEX exceeds revenue.
   - Payroll dominates expenses.

 Without structural cost reduction or revenue improvement, the operating model appears unsustainable.

---

##  Technical Highlights

- Data modeling with star-schema approach
- Custom DAX measures:
  - Cash bridge logic
  - OTP calculation
  - Risk segmentation
  - Dynamic insights (Top Expense Driver)
- Conditional formatting driven by business rules
- Interactive filtering across dashboards

---

##  Dataset

Synthetic dataset designed to simulate real treasury operations:

- Treasury transactions
- Cash balance daily table
- Counterparty master data

---

##  Tools Used

- Power BI
- DAX
- Power Query
- Data modeling (Dim/Facts architecture)

---

##  Author Notes

This project focuses not only on visualization but on translating financial data into actionable business insights.

The goal was to emulate a realistic financial analyst workflow, from treasury monitoring to operational risk analysis.
