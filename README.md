# Fleet CII & Fuel Analysis Dashboard

## 📊 Project Overview

A comprehensive Excel-based fleet performance analysis tool for the shipping industry. This project analyzes 1,440 voyages across 120 ships, providing actionable insights on carbon intensity (CII), fuel efficiency, and regulatory compliance.

**Built with:** Microsoft Excel (Tables, PivotTables, Advanced Formulas, Conditional Formatting, Interactive Dashboard)

---

## 🎯 Key Features

- **📈 5+ Interactive Charts** — Monthly trends, CII by ship type, rating distribution, weather impact, rating by ship type
- **📋 A-E CII Ratings** — IMO-compliant rating system per ship (best-in-class A, worst E)
- **🎛️ Dynamic Slicers** — Filter by ship type, month, fuel type with one click
- **📄 Executive Summary** — One-page Fleet Manager brief with actionable recommendations
- **🌊 Weather Impact Analysis** — Quantifies CII variation across calm, moderate, and stormy conditions
- **🔍 Data Quality Assurance** — Missing value verification, outlier detection, CO₂ cross-check

---

## 💡 Key Insights

| Insight | Finding |
|---------|---------|
| **At-Risk Vessels** | 26 ships (21.7% of fleet) rated D/E |
| **Priority Classes** | Oil Service Boat & Tanker Ship — 13 D/E ships each |
| **Weather Impact** | Significant (17.2% variation) — stormy CII 19% higher than calm |
| **Efficiency Alert** | Voyages below 75% engine efficiency flagged for review |
| **CO₂-Fuel Link** | Emissions derived from fuel consumption (2.7-3.1 kg CO₂/kg fuel) |

---

## 📂 Workbook Structure

| Sheet | Contents |
|-------|----------|
| **Data** | Voyages table — 1,440 rows, 13 columns with formulas |
| **Analysis** | PivotTables for all visualizations |
| **Ratings** | 120 ships with percentiles and A-E ratings |
| **Dashboard** | 5 charts, KPIs, slicers, insights |
| **Executive Summary** | One-page Fleet Manager brief |

---

## 🛠️ Technical Skills Demonstrated

- **Excel Tables** — Structured references, dynamic ranges, auto-fill formulas
- **Advanced Formulas** — XLOOKUP, INDEX/MATCH, COUNTIFS, SUMIFS, array formulas
- **PivotTables** — 9 interconnected pivots for multi-dimensional analysis
- **Data Modeling** — DWT lookup, CII calculation, percentile ranking
- **Conditional Formatting** — Highlight low efficiency, color-coded A-E ratings
- **Dashboard Design** — KPIs, slicers, charts, no gridlines, clean canvas
- **Data Validation** — Missing value checks, outlier detection, cross-validation

---

## 🚀 How to Use

1. Download `Fleet_CII_Fuel_Analysis.xlsx`
2. Open in Excel (2016 or later)
3. Navigate to the **Dashboard** sheet
4. Use slicers to filter by ship type, month, or fuel type
5. View the **Executive Summary** for key insights
6. Explore the **Data** and **Analysis** sheets for deeper investigation

---

## 📝 Regulatory Context

- **CII (Carbon Intensity Indicator)** — IMO regulation for ship efficiency
- **SEEMP Part III** — Corrective action plans for E-rated vessels
- **MRV (Monitoring, Reporting, Verification)** — EU emissions compliance
- **IMO 2020** — Sulfur cap regulations

---

## 🔧 Future Enhancements

- [ ] Automate data refresh with Power Query
- [ ] Add vessel-specific speed and load data
- [ ] Integrate fuel price analysis
- [ ] Build Power BI version for real-time monitoring
- [ ] Add route optimization recommendations

---

## 📄 License

This project is for demonstration purposes. Please contact the author for commercial use.

---

**⭐ If you find this useful, please star the repository!**
