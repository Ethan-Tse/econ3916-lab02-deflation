# econ3916-lab02-deflation
ECON3916 Lab 02 - Measurement and Indexes
Deflating Economic Data — Nominal vs. Real

Objective: This project quantifies the erosion of purchasing power over time by converting nominal wage and price data into inflation-adjusted (real) terms using CPI-based deflation techniques.

Methodology:

Retrieved Consumer Price Index (CPI) and average hourly earnings series directly from the FRED API (no key required)
Implemented a custom deflate_series() function to convert nominal dollar figures into constant 2020 dollars
Applied the deflation function to hourly earnings data to isolate real wage growth from inflationary effects
Extended the analysis to a real-world price index (the Big Mac) to compare nominal vs. real price appreciation against overall CPI movement
Built an interactive deflation explorer allowing users to adjust the base year via a slider and observe how the choice of reference year affects real-value calculations

Key Findings:

Nominal hourly earnings showed steady growth over the sample period, but after adjusting for inflation, real earnings growth was noticeably more modest — underscoring the gap between headline wage gains and actual purchasing power
The Big Mac's nominal price rose considerably faster than its inflation-adjusted price, with a meaningful share of that increase attributable to broad CPI growth rather than a genuine rise in real value
Together, these results demonstrate that nominal figures alone can overstate economic gains, and that deflation is essential for meaningful longitudinal comparisons
