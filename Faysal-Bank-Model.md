# 3-Statement Financial Model & Valuation: Faysal Bank Limited

## 🎯 The Problem
Commercial bank financial statements break standard corporate 3-statement templates due to unique liquidity structures, interest spreads, and non-cash loan provisions. Treating customer deposits or bond investments under typical retail inventory metrics results in massive cash flow imbalances.

## 🛠️ The Technical Action
* Developed a fully dynamic 3-statement engine mirroring State Bank of Pakistan (SBP) banking guidelines.
* Isolated and accounted for complex non-cash items: added back provisioning expenses against non-performing loans (NPLs) and handled negative credit allowance reversals (provisions written back to the income statement) by creating dynamic subtraction formulas to prevent artificial profit inflation.
* Neutralized reclassification errors by calculating changes across *Net Advances* to automatically reconcile bad debt write-offs.
* Bypassed standard corporate turnover metrics to build bank-specific indicators, including the **Advances-to-Deposits Ratio (ADR)** and **Investments-to-Deposits Ratio (IDR)**.

## 🚀 The Result
Delivered a fully integrated forecasting model where changes to macroeconomic inputs or deposit growth scales dynamically across all three sheets while maintaining an automated "Error Check" row perfectly tied to zero. 

### 📸 Model Architecture Snapshot
`![Model Layout](your-image-name.png)`)*
