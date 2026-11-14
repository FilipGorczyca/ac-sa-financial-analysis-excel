<div align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/English-Active-0A66C2?style=flat-square" alt="English"></a>
  <a href="./README.pl.md"><img src="https://img.shields.io/badge/Polski-Przelacz_jezyk-dc143c?style=flat-square" alt="Polski"></a>
</div>

# Financial Statement Analysis of AC S.A. (2018-2020)

**Author:** Filip Gorczyca  
**Field of Study:** Economic Analytics, Krakow University of Economics (UEK)

---

## Project Overview
Financial health, operational efficiency, and long-term stability analysis of **AC S.A.** (a leading European manufacturer of automotive LPG/CNG fuel systems under the **STAG** brand) for the years **2018-2020**, benchmarked against automotive sector averages.

## Repository Contents
| File | Description |
| :--- | :--- |
| [`Ocena kondycji finansowej AC S.A. (2018-2020).pdf`](./Ocena%20kondycji%20finansowej%20AC%20S.A.%20(2018-2020).pdf) | Full analytical report (22 pages, PL) with financial statements, ratio tables, discriminant models, and interpretations. |
| [`ocena kondycji finansowej przedsiębiorstwa.xlsx`](./ocena%20kondycji%20finansowej%20przedsiębiorstwa.xlsx) | Source MS Excel workbook (14 sheets) containing calculations, vertical/horizontal analysis, financial ratios, DuPont model, Altman Z-Score, and SWOT. |

---

## Key Financial Results (2018-2020)

### 1. Financial Statements Summary (in thousand PLN)
| Metric | 2018 | 2019 | 2020 | Change (2018-2020) |
| :--- | ---: | ---: | ---: | :---: |
| **Net Sales Revenue** | 237 426 | 222 682 | 185 222 | -21.99% |
| **Operating Profit (EBIT)** | 49 562 | 46 283 | 36 767 | -25.82% |
| **Net Income** | 39 009 | 38 183 | 30 898 | -20.79% |
| **Total Assets** | 166 433 | 174 768 | 196 937 | +18.33% |
| **Total Equity** | 111 812 | 114 691 | 132 445 | +18.45% |
| **Operating Cash Flow** | 50 690 | 41 601 | 18 841 | -62.83% |

### 2. Core Financial Ratios vs. Industry Benchmarks
| Category | Financial Ratio | 2018 | 2019 | 2020 | Benchmark (2020) | Assessment |
| :--- | :--- | ---: | ---: | ---: | ---: | :--- |
| **Profitability** | Gross Margin on Sales (`RS`) | 20.85% | 19.82% | 17.41% | 5.30% | Above sector average |
| **Profitability** | Net Profit Margin (`ZD`) | 16.24% | 16.80% | 16.07% | 4.21% | Above sector average |
| **Profitability** | Return on Assets (`ROA / ZOM`) | 23.44% | 22.38% | 17.22% | 5.01% | Above sector average |
| **Profitability** | Return on Equity (`ROE / ZKW`) | 34.89% | 33.72% | 25.82% | 9.65% | Above sector average |
| **Liquidity** | Current Ratio (`WPI`) | 2.46 | 1.79 | 1.84 | 0.35 | High liquidity |
| **Liquidity** | Quick Ratio (`WPII`) | 0.83 | 0.55 | 0.57 | 0.97 | Below benchmark (high inventory) |
| **Efficiency** | Days Inventory Outstanding (`WOZ`) | 121.9 d | 128.5 d | 165.8 d | ~7.5 d | Capital tied up in stock |
| **Efficiency** | Cash Conversion Cycle (`CSP`) | 74.4 d | 105.3 d | 157.8 d | 13.0 d | Extended cash cycle |
| **Leverage** | Total Debt Ratio (`SZ`) | 32.82% | 34.38% | 32.75% | 48.10% | Low financial risk |
| **Leverage** | Financial Structure Stability (`TSF`) | 139.09% | 122.60% | 128.50% | 130.00% | Stable long-term funding |

### 3. Multi-Factor & Discriminant Models
* **DuPont 3-Step Decomposition (ROE = Net Margin * Asset Turnover * Equity Multiplier):**
  * **2018:** 16.24% * 1.443 * 1.489 = 34.89%
  * **2019:** 16.80% * 0.666 * 1.524 = 33.72% (change: -1.17 pp)
  * **2020:** 16.07% * 0.357 * 1.487 = 25.82% (change: -7.89 pp)
  * *Conclusion:* The decline in ROE resulted mainly from lower asset turnover (drop from 1.44 to 0.36), while net margin remained high (~16%).
* **Altman Z-Score:** 3.68 (2018) -> 3.25 (2019) -> 2.68 (2020) - safe financial standing with a downward trend caused by slower asset rotation.
* **Discriminant Model (ZH):** 2.14 (2018) -> 1.51 (2019) -> 1.47 (2020) - positive values across all periods confirm no bankruptcy threat.

## Conclusions
1. **Profitability:** AC S.A. achieves margins significantly higher than automotive industry averages, with a positive financial leverage effect (`WDF` between 9.98 and 11.57).
2. **Capital Structure:** Low total debt (~33% of total assets) and high equity (132.4M PLN in 2020) ensure long-term solvency.
3. **Working Capital:** Rising inventory levels (50.6M PLN in 2018 vs. 61.2M PLN in 2020) extended the inventory conversion period to 165.8 days and the Cash Conversion Cycle to 157.8 days.
