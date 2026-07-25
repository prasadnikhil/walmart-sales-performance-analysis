# walmart-sales-performance-analysis
"Excel analysis of 421K+ Walmart sales records — pivot tables, VLOOKUP, dashboard and business insights"
# 🛒 Walmart Sales Performance Analysis (2010–2012)

### 🎯 Brief Project Info :-

- I built a Walmart Sales Performance Analysis using Excel, combining pivot tables, VLOOKUP-based store classification, and formula-driven KPIs.
- The report highlights key patterns in sales by store type, holiday impact, department performance, markdown effectiveness, and economic sensitivity.
- The final analysis offers a clear, data-driven view of what actually drives Walmart's weekly revenue.

---

## 📍 Key KPI Highlights

| Metric | Value |
|---|---|
| **Total Sales Analyzed** | **$6.74B** |
| **Records Analyzed** | 421,570 weekly sales rows |
| **Stores Covered** | 45 (Types A, B, C) |
| **Time Period** | 2010–2012 |
| **Holiday Sales Lift** | **+7.1%** vs regular weeks |

**Key Insight:** Even though holiday weeks make up a small fraction of the calendar, they consistently outperform regular weeks — a **7.1% lift** worth planning inventory and staffing around.

---

## 🏬 By Store Type

| Store Type | Total Sales | % Share |
|---|---|---|
| **Type A** | **$4.33B** | **64.3%** |
| Type B | $2.00B | 29.7% |
| Type C | $0.41B | 6.0% |

**Key Insight:** Type A (large-format) stores generate almost **two-thirds of all revenue**, despite being only one of three store formats — a strong signal for where expansion investment pays off most.

---

## 📈 Holiday vs Non-Holiday Sales

| Week Type | Avg Weekly Sales |
|---|---|
| **Holiday Week** | **$17,036** |
| Non-Holiday Week | $15,901 |

**Insight:** Holiday weeks (Thanksgiving, Christmas, Super Bowl, Labor Day) show a consistent, measurable lift — useful for forecasting seasonal staffing and stock levels.

---

## 🏆 Top 5 Departments by Revenue

| Department | Total Sales |
|---|---|
| **Dept 92** | **$484M** |
| Dept 95 | $449M |
| Dept 38 | $393M |
| Dept 72 | $306M |
| Dept 90 | $291M |

**Key Insight:** A small handful of departments drive a disproportionate share of total revenue — the classic 80/20 pattern retail chains plan floor space around.

---

## 🏷 Markdown Campaign Effectiveness

| Markdown Status | Avg Weekly Sales |
|---|---|
| **Had Markdown** | **$16,177** |
| No Markdown | $15,872 |

**Insight:** Weeks with an active markdown/promo show modestly higher average sales — a small but real lift that supports continuing promotional campaigns.

---

## 📊 Economic Sensitivity (CPI & Unemployment)

- Average weekly sales stayed **largely flat across both CPI and unemployment ranges**, with no strong downward trend even in high-inflation or high-unemployment periods.
- **Insight:** This is consistent with Walmart's position as a value-oriented retailer — consumers tend to shift spending *toward* low-cost retailers during economic pressure, not away from them.

---

## 🏆 Store Efficiency (Sales per Square Foot)

- Ranked all 45 stores by **Sales per Square Foot** rather than raw total sales — a fairer comparison between large and small-format stores.
- Classified stores into **High / Medium / Low Efficiency** tiers using a VLOOKUP-based lookup table.

| Performance Tier | Total Sales |
|---|---|
| **Medium Efficiency** | **$2.73B** |
| Low Efficiency | $2.13B |
| High Efficiency | $1.88B |

**Key Insight:** Several smaller-format stores ranked in the **High Efficiency** tier despite lower total revenue — proving that raw sales totals alone can be misleading without adjusting for store size.

---

## High-Level Insights Summary

🔥 **Top Revenue Drivers**
1. **Type A (large-format) stores** — 64.3% of total revenue
2. **Holiday weeks** — consistent +7.1% sales lift
3. **Top 5 departments** — disproportionate share of total sales
4. **Active markdown campaigns** — modest but real sales lift

📉 **Economic Resilience**
- Sales remain stable regardless of CPI or unemployment level — Walmart shows low sensitivity to macroeconomic downturns.

🏬 **Efficiency Over Size**
- Store size alone doesn't predict performance — several smaller stores outperform larger ones on a per-square-foot basis.

---

## 💡 Recommendations

1. **📦 Prioritize Inventory for Holiday Weeks:** Increase stock and staffing ahead of major holidays given the consistent sales lift.
2. **🏬 Focus Expansion on Large-Format (Type A) Stores:** These deliver the highest revenue share and warrant continued investment.
3. **🏷 Continue Targeted Markdown Campaigns:** The modest but real lift justifies keeping promotional activity, especially in underperforming departments.
4. **📊 Use Sales-per-SqFt, Not Just Totals, for Store Reviews:** Adjust performance evaluations for store size to avoid rewarding large stores by default.
5. **🌎 Don't Over-React to Economic Indicators:** Since sales are resilient to CPI/unemployment shifts, forecasting models shouldn't over-weight macroeconomic swings.

---

## Dashboard & Pivot Table Images :-

![pivot table overview](pivot-tables-overview.png)

![store efficiency chart](store-efficiency-chart.png)

## Tools & Techniques Used

`Excel` `Pivot Tables` `VLOOKUP` `Data Cleaning` `Chart Visualization`

- Cleaned and merged 3 source files (sales, store attributes, economic/promo data) into one 421,570-row dataset
- Handled missing values (markdown blanks filled with 0), flagged negative sales as returns, added derived time columns
- Built 7 pivot tables answering distinct business questions
- Used VLOOKUP to classify all 45 stores into performance tiers based on efficiency ranking

## About

Excel-based sales performance analysis using real, publicly available Walmart transactional data (2010–2012).
