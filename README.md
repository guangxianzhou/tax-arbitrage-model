# Tax Arbitrage & Wealth Friction Model (W-2 vs. LTCG)

An institutional-grade comparative financial model quantifying the tax wedge between earned wage income (W-2) and long-term capital gains (LTCG) under US federal and state tax frameworks.

## Key Financial Insights ($150,000 Baseline)
- **FICA Tax Friction:** W-2 wages incur an immediate 7.65% ($11,475) payroll drag. Long-term capital gains are completely FICA-exempt.
- **Preferential Federal Brackets:** Earned income is heavily penalized by progressive federal tiers, whereas capital gains leverage a 15% preferential rate with the first $47,025 taxed at 0%.
- **Net Cash Advantage:** On an identical $150,000 inflow, the capital structure generates **+$23,757 (+22.9%)** more net cash in hand and lowers the effective tax rate from **30.99%** down to **15.16%**.

## Model Architecture
- **Inputs:** Hardcoded variables in blue (Gross Inflows, Standard Deductions).
- **Formulas:** Fully dynamic nested `IF` statements mapping progressive IRS brackets.
- **Tools:** Built in Google Sheets/Excel, formatted for wealth management portfolio and tax planning reviews.
