# 📊 Executive Financial Performance & SaaS Analytics Platform

> **Executive Summary:** A strategic Power BI intelligence suite designed to transform fragmented SaaS billing and ledger data into CFO-ready insights. This platform automates the calculation of unit economics, capital structure ratios, and cross-entity performance benchmarking.

---

### 🎯 Business Intelligence Objectives
Senior leadership requires decision signals, not just data. This platform provides:
- **Unit Economic Transparency:** Deep dives into MRR/ARR growth and retention tiers.
- **Capital Structure Analysis:** Automated calculation of ROE, Debt-to-Equity, and Liquidity ratios.
- **Risk Governance:** Real-time "Traffic Light" logic to flag subsidiaries under-performing against target hurdle rates.

### 🛠️ Data Architecture & Governance
- **Data Modeling:** Implemented a **Star Schema** to optimize DAX performance and ensure report scalability.
- **ETL Process:** Utilized Power Query (M) to normalize inconsistent raw ledger files into a unified reporting format.
- **DAX Engineering:** Custom time-intelligence measures for Revenue CAGR, Year-over-Year (YoY) growth, and Risk Signaling.

---

### 📊 Dashboard Intelligence Layers

#### 1. Executive Summary (The "CFO View")
High-level KPIs for board reporting, including revenue velocity, net margins, and risk signals.
![Executive Summary](screenshots/Executive%20summary.png)

#### 2. Revenue & Growth Analysis
Breakdown of subscription lifecycle metrics, focusing on growth trends and billing cycle distribution.
![Revenue Analysis](screenshots/Revenue%20Analysis.png)

#### 3. Capital Ratios & Risk Benchmarking
Side-by-side comparison of company performance, highlighting leverage (Debt-to-Equity) and profitability (ROE).
![Ratios Overview](screenshots/Ratios%20Overview.png)

#### 4. Comparative Entity Performance
Benchmark view using gauge charts to measure critical metrics against internal 15% ROE targets.
![Benchmark Dashboard](screenshots/Benchmark%20Dashboard.png)

---

### 🚀 Technical Competencies Demonstrated
- **Advanced DAX:** Complex CAGR variables, SWITCH-based conditional formatting, and ALLEXCEPT filter context.
- **Financial Modeling:** Mastery of SaaS unit economics (MRR/ARR) and leverage ratios.
- **UX/UI for Finance:** High-density information design using consistent color theory for executive readability.

---

### ⚙️ How to Explore This Project
1. **Source Code:** Review the custom financial logic in `scripts/measures.dax`.
2. **Data Model:** View the star-schema structure in `screenshots/Data_Model_Schema.png`.
3. **Interactive File:** Download `Project1-Dashboard.pbix` to explore the full interactivity.

**👨‍💻 Recruiter Note:** This project demonstrates the ability to bridge the gap between raw financial data and capital allocation decisions—directly applicable to FP&A, Finance Transformation, and CFO-office roles.
