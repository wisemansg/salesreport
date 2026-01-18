# 🛍️ Sales Report Dashboard (2021)

This dashboard analyzes company sales performance in 2021 using **Power BI**. It transforms raw sales data into interactive visuals (charts, tables, maps) to help managers and stakeholders quickly understand sales trends, category performance, and geographic distribution. The report focuses on product categories like novelty items, supermarket goods, computers, gifts, and corporate supplies.

---

## 🎯 Project Objective

Provide business intelligence insights to support decisions regarding:

- Product focus  
- Market expansion  
- Seasonal strategies  
- Overall sales performance  

The dashboard answers key questions about sales trends, category contributions, monthly fluctuations, and regional performance.

---

## 📁 Dataset Used

The dataset contains 12 months of sales records for 2021, including fields such as:

- Date of sale (month/year)  
- Product category  
- Sales amount  
- Quantity sold  
- Geographic location (state/province)  
- Year  

Dataset Link: `<a href="(PROJECT1) CustomerMaster.csv">Sales_Report_2021.csv</a>`

---

## ❓ Questions (KPIs)

Key KPIs explored:

- Total Sales  
- Total Quantity Sold  
- Year-over-Year (YoY) Change  
- Sum of Sales YTD (Year-to-Date)  
- Sales by Category  
- Sales by Month  
- Sales by Province/State  
- Quantity Trends  

---

## ⚙️ Process

1. **Data Preparation**: Cleaned sales data in Power BI, standardized product categories, handled missing months, and formatted numeric values.  
2. **Data Modeling**: Created calculated columns for YTD sales, monthly YoY change, and cumulative quantity.  
3. **KPI Logic (DAX/Formulas)**: Metrics such as total sales, % YoY, total quantity, and category contributions.  
4. **Exploratory + Comparative Analytics**: Analyzed trends by month, category, and state.  
5. **Visualization (Power BI)**: Built interactive charts, tables, and maps with slicers for year filtering.

---

## 🖥️ Dashboard Overview

### 1️⃣ Year Filters
Checkbox filter allowing selection of one or multiple years (2018–2021).  
- **2021 Selected**: all visuals reflect this year.  
- **Use**: Compare trends across years.

### 2️⃣ Sales by Category (Bar Chart)  
- **Novelty Shop**: ~$16M (~70% of sales)  
- **Supermarket**: ~$2M  
- **Computer**: ~$2M  
- **Gift**: ~$2M  
- **Corporate**: ~$0  

**Insight**: Novelty items dominate; diversification may reduce dependency risk.

### 3️⃣ Monthly Sales Breakdown (Table)  

| Month     | Sum of Sales | % YoY Change | Sum of Sales YTD |
|-----------|-------------|--------------|----------------|
| January   | $4,440,581  | +3.1%        | $4,440,581     |
| February  | $4,246,148  | -4.3%        | $8,686,729     |
| March     | $4,588,420  | -8.2%        | $13,175,149    |
| April     | $4,594,222  | +11.4%       | $17,769,371    |
| May       | $4,594,222  | -100.0%      | $22,363,593    |
| June      | $4,594,222  | -100.0%      | $22,363,593    |
| July      | $0          | -100.0%      | $22,363,593    |
| August    | $0          | -100.0%      | $22,363,593    |
| September | $0          | -100.0%      | $22,363,593    |
| October   | $0          | -100.0%      | $22,363,593    |
| November  | $0          | -100.0%      | $22,363,593    |
| December  | $2,748,351  | -100.0%      | $22,748,351    |
| **Total** | $22,748,351 | -57.98%      | $22,748,351    |

**Insight**: Strong H1, sharp decline in H2. Potential supply or market issues.

### 4️⃣ Sales by Province/State (Map)  
- Darker blue = higher sales  
- **Top States**: California, Texas, New York  
- **Low Sales**: Western & Midwest regions  
- **Insight**: Focus marketing in low-performing regions to increase coverage.

### 5️⃣ Quantity Trend by Month (Line Chart)  
- Starts high (~220,000 units in Jan), dips mid-year, near zero in later months.  
- **Insight**: Confirms H2 drop in sales volume.

---

## 📊 Project Insights

- **Strong Start, Weak Finish**: Solid Q1/Q2 sales, drastic H2 drop (-58% YoY).  
- **Category Dominance**: Novelty items drive ~70% of total sales.  
- **Geographic Opportunities**: Expand marketing in weaker states while leveraging top-performing states.  
- **Operational Recommendation**: Investigate causes of mid-year drop; monitor monthly trends via Power BI alerts.

---

## ✅ Final Conclusion

The 2021 Sales Report dashboard provides stakeholders with:

- Clear visualization of product, monthly, and geographic performance  
- Identification of top-performing categories (Novelty items)  
- Early detection of sharp sales decline in H2  
- Insights for marketing, inventory, and product strategy

---

## 🛠️ Tools Used

Power BI · Power Query · DAX · Excel/CSV

---

## 🚀 Live Dashboard Link

[View Dashboard](https://app.powerbi.com/view?r=EXAMPLE_DUMMY_LINK)
