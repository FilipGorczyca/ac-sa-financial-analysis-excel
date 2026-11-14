<div align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/🇬🇧_English-Active-0A66C2?style=for-the-badge" alt="English"></a>
  <a href="./README.pl.md"><img src="https://img.shields.io/badge/🇵🇱_Polski-Przełącz_język-dc143c?style=for-the-badge" alt="Polski"></a>
</div>

# 📊 Financial Statement Analysis of AC S.A. (2018–2020)

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Corporate Finance](https://img.shields.io/badge/Corporate_Finance-0A66C2?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

**Author:** Filip Gorczyca  
**Field of Study:** Economic Analytics, Krakow University of Economics (UEK)

---

## 📌 Project Overview
Comprehensive assessment of the financial health, operational efficiency, and long-term stability of **AC S.A.** (a leading European manufacturer of automotive LPG/CNG fuel systems under the **STAG** brand) for the years **2018–2020**, benchmarked against automotive sector averages.

## 📂 Repository Contents
| File | Description |
| :--- | :--- |
| 📄 [`Ocena kondycji finansowej AC S.A. (2018-2020).pdf`](./Ocena%20kondycji%20finansowej%20AC%20S.A.%20(2018-2020).pdf) | **Full analytical report (22 pages, PL)** with formatted financial statements, ratio tables, discriminant models, and interpretations. |
| 📗 [`ocena kondycji finansowej przedsiębiorstwa.xlsx`](./ocena%20kondycji%20finansowej%20przedsiębiorstwa.xlsx) | **Source MS Excel workbook (14 sheets)** containing full calculations, vertical/horizontal analysis, ratios, DuPont model, Altman Z-Score, and SWOT. |

---

## 📈 Key Financial Highlights (2018–2020)

### 1. Financial Statements Summary (in thousand PLN)
| Metric | 2018 | 2019 | 2020 | Change (2018–2020) |
| :--- | ---: | ---: | ---: | :---: |
| **Net Sales Revenue** | 237,426 | 222,682 | 185,222 | 📉 -21.99% |
| **Operating Profit (EBIT)** | 49,562 | 46,283 | 36,767 | 📉 -25.82% |
| **Net Income** | 39,009 | 38,183 | 30,898 | 📉 -20.79% |
| **Total Assets** | 166,433 | 174,768 | 196,937 | 📈 +18.33% |
| **Total Equity** | 111,812 | 114,691 | 132,445 | 📈 +18.45% |
| **Operating Cash Flow** | 50,690 | 41,601 | 18,841 | 📉 -62.83% |

### 2. Core Financial Ratios vs. Industry Benchmarks
| Category | Financial Ratio | 2018 | 2019 | 2020 | Industry Benchmark (2020) | Assessment |
| :--- | :--- | ---: | ---: | ---: | ---: | :--- |
| **Profitability** | Gross Margin on Sales (`RS`) | 20.85% | 19.82% | 17.41% | 5.30% | ✅ Outperforming sector |
| **Profitability** | Net Profit Margin (`ZD`) | 16.24% | 16.80% | 16.07% | 4.21% | ✅ Outperforming sector |
| **Profitability** | Return on Assets (`ROA / ZOM`) | 23.44% | 22.38% | 17.22% | 5.01% | ✅ Outperforming sector |
| **Profitability** | Return on Equity (`ROE / ZKW`) | 34.89% | 33.72% | 25.82% | 9.65% | ✅ Outperforming sector |
| **Liquidity** | Current Ratio (`WPI`) | 2.46 | 1.79 | 1.84 | 0.35 | ✅ Strong liquidity |
| **Liquidity** | Quick Ratio (`WPII`) | 0.83 | 0.55 | 0.57 | 0.97 | ⚠️ Below benchmark (inventory) |
| **Efficiency** | Days Inventory Outstanding (`WOZ`) | 121.9 d | 128.5 d | 165.8 d | ~7.5 d | ❌ Capital tied up in stock |
| **Efficiency** | Cash Conversion Cycle (`CSP`) | 74.4 d | 105.3 d | 157.8 d | 13.0 d | ⚠️ Extended cash cycle |
| **Leverage** | Total Debt Ratio (`SZ`) | 32.82% | 34.38% | 32.75% | 48.10% | ✅ Low financial risk |
| **Leverage** | Financial Structure Stability (`TSF`) | 139.09% | 122.60% | 128.50% | 130.00% | ✅ Stable long-term funding |

### 3. Multi-Factor & Discriminant Models
* **DuPont 3-Step Decomposition ($ROE = \text{Net Margin} \times \text{Asset Turnover} \times \text{Equity Multiplier}$):**
  * **2018:** $16.24\% \times 1.443 \times 1.489 = 34.89\%$
  * **2019:** $16.80\% \times 0.666 \times 1.524 = 33.72\%$ ($\Delta = -1.17\text{ pp}$)
  * **2020:** $16.07\% \times 0.357 \times 1.487 = 25.82\%$ ($\Delta = -7.89\text{ pp}$)
  * *Finding:* The gradual decline in ROE was driven primarily by lower asset turnover (`1.44` $\rightarrow$ `0.36`), while net margin remained exceptionally resilient (`~16%`).
* **Altman Z-Score:** `3.68` (2018) $\rightarrow$ `3.25` (2019) $\rightarrow$ `2.68` (2020) – confirms overall solvency with a downward trend resulting from slower asset rotation.
* **Discriminant Model ($Z_H$):** `2.14` (2018) $\rightarrow$ `1.51` (2019) $\rightarrow$ `1.47` (2020) – positive values across all periods indicate low bankruptcy risk.

## 🔍 Key Strategic Takeaways
1. **Superior Profitability:** AC S.A. consistently achieves margins three to four times higher than automotive industry averages, supported by a positive financial leverage effect (`WDF` between `9.98` and `11.57`).
2. **Conservative Capital Structure:** Low total debt (`~33%` of total assets) and a strong equity base (`132.4M PLN` in 2020) provide high long-term solvency.
3. **Working Capital Bottleneck:** Rising inventory levels (`50.6M PLN` in 2018 $\rightarrow$ `61.2M PLN` in 2010) extended the inventory conversion period to `165.8 days` and the Cash Conversion Cycle to `157.8 days`. Optimizing inventory management is key to unlocking free cash flow.
