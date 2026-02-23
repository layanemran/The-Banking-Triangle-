![Project Header](images/Header.png)
## The Banking Triangle 

This project analyzes the performance of the Saudi banking sector by examining the dynamic relationship between central bank monetary policies and market outcomes. Within the broader framework of Saudi Vision 2030, the financial sector serves as a critical driver of economic transformation and housing market expansion.

The analysis is structured around a strategic analytical triangle: **monetary policy** (interest rates – SAIBOR), **consumer credit behavior** (mortgage financing), and **institutional profitability** (net banking performance). 

The central question addressed by this dashboard is: 
> "To what extent do fluctuations in interest rates (SAIBOR) influence mortgage financing volumes and the overall profitability of Saudi banks?"

By answering this question, the dashboard provides stakeholders with a clear, data-driven visualization of how macroeconomic decisions cascade through the financial system — impacting both individual borrowers and major banking institutions.

## 🗄️Data Source
 The analytical foundation of this project is built on officially published data sourced from the Saudi Central Bank (SAMA) Open Data Portal. This source was selected to ensure institutional reliability and reflect the most accurate macro-financial indicators within the Kingdom.
 To complement the macroeconomic data, financial statements and banking performance reports were also obtained from the Saudi Exchange (Tadawul). This source was used to collect quarterly financial data of listed Saudi banks, including net profits, total assets, and dividend distributions, allowing for a deeper analysis of institutional profitability trends.

 The dataset spans from 2021 to 2025 and includes a combination of time-series and categorical financial data, structured into three main components:

1. **Monetary Indicators:** The 3‑month SAIBOR (Saudi Interbank Offered Rate), serving as the benchmark for lending rates.
2. **Lending Dynamics:** Detailed data on new residential mortgage financing (categorized into Villas, Apartments, and Land) alongside consumer lending activity.
3. **Banking Performance:** Key financial indicators including Total Assets, Total Deposits, and Quarterly Net Profits across the Saudi banking sector.

Together, these sources enable an integrated analysis of how monetary policy shifts are associated with mortgage financing trends and overall banking sector performance.

---
📂 **Project Assets:**
* All raw and processed datasets are available in the [data directory](https://github.com/layanemran/The-Banking-Triangle-/tree/main/data).


## ⚙️ Steps & Methodology
To transform raw institutional financial data into a structured and strategic dashboard, I followed a multi-stage analytical workflow designed to ensure accuracy, consistency, and clarity.

### 1. Data Cleaning & Transformation
**Standardization:**
All monetary values were unified into SAR (Millions/Billions) to maintain consistent scaling across datasets collected from SAMA and Tadawul. This ensured comparability between macroeconomic indicators and bank-level financial performance.

**Time-Series Alignment:**
Quarterly bank financial reports were carefully realigned with monthly SAIBOR data to construct a synchronized analytical timeline spanning from 2021 to 2025. This alignment was critical for accurately examining temporal relationships between monetary policy changes and banking outcomes.

**Metric Engineering & Data Adjustment**
Using Excel, I engineered additional calculated fields to enhance analytical depth and ensure data completeness.

Excel was primarily used for data preprocessing, validation checks, structural organization, and controlled metric engineering prior to visualization deployment.
During preprocessing, certain Q4 values were partially incomplete in the published datasets. To maintain quarterly continuity and analytical consistency, I aggregated available sub-period values where appropriate and validated them against annual summaries .

Additional calculated fields included:
-Demand Deposits
-Time_Deposits

### 2. Analysis Approach
**The Triangle Framework**
The analytical structure of the dashboard is built around three interconnected pillars:

1- Monetary Policy (Interest Rates – SAIBOR)

2- Consumer Credit Behavior (Mortgage Financing Trends)

3- Institutional Performance (Bank Profitability & Assets Growth)

"This framework enables a layered understanding of how macro-level policy decisions cascade into consumer financing behavior and ultimately impact institutional financial strength."

**Relationship Exploration:**
Rather than presenting isolated KPIs, the dashboard explores the inverse relationship between SAIBOR movements and mortgage financing volumes to assess market sensitivity during tightening cycles.

The goal was not merely to visualize trends, but to reveal how liquidity conditions and rate environments are associated with shifts in credit growth and banking sector performance.

### 3. Tool Selection
**Tableau:**
Selected for its advanced interactive capabilities, dynamic filtering, and drill-down features. Tableau allows stakeholders to explore financial metrics across time and categories without technical complexity, supporting clear insight discovery.

**Excel:**
Used for structured preprocessing, data validation, calculated field creation, and temporal synchronization before visualization deployment.

### 4. Design Decisions (UI/UX)
A dark-mode interface was intentionally selected to reflect a professional FinTech environment, enhance visual contrast for key performance indicators, and reduce visual fatigue during extended exploration.

**Navigation Hierarchy:**
The dashboard layout was structured hierarchically, guiding the viewer from macroeconomic indicators toward micro-level banking performance. A custom navigation bar was implemented to simulate a professional analytics platform interface, enabling intuitive movement between sections (Overview, Mortgage Dynamics, Profitability).

**Clarity & Accessibility:**
All tooltips and labels were refined to explain complex financial metrics in clear, professional English suitable for non-technical stakeholders. The objective was to ensure that the dashboard remains both analytically rigorous and easy to interpret.



