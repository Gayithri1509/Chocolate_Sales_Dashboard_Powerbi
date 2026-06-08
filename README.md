# 🍫 Chocolate Sales Analytics Dashboard — Power BI



![Dashboard Preview](screenshots/main_dashboard.png)



## 📌 Project Overview
An end-to-end business intelligence dashboard built in 
Power BI analyzing chocolate product sales across 
multiple geographies, salespersons, and time periods.

---

## 📊 Dashboard Pages

| Page | Description |
|------|-------------|
| Main Dashboard | KPI overview with slicers and top visuals |
| Amount by Product | Product-wise revenue breakdown |
| Profits Analysis | Profit % by geography and product |
| Shipment Distribution | Shipment trends by month and team |
| Amount Per Box | Salesperson efficiency by region |
| Top N Persons | Top performer profit analysis |
| Comparing YOY | Year-over-Year variance analysis |
| Team Improvements | Team-level sales benchmarking |

---

## 💡 Key Insights
- 💰 Total Revenue: **$141M** across all regions
- 📦 Total Boxes Shipped: **9M**
- 📈 Overall Profit %: **57.3%**
- 🏆 Top Salesperson: **Suman Katte** ($10.5M)
- 🍫 Top Product: **Organic Choco Syrup** ($4.9M)
- 🌍 Largest Market: **India** (28.65%)
- ⚠️ Loss-making products: 85% Dark Bars, 
  Baker's Choco Chips, After Nines

---

## 🛠️ Tools & Techniques Used
- **Power BI Desktop** — Dashboard creation
- **DAX Measures** — Custom KPIs and calculations
- **Power Query** — Data transformation
- **PowerPoint** — Custom background design
- **Data Modeling** — Multi-table relationships

---

## 📐 DAX Measures Created (shipments table)

| Measure | Purpose |
|---------|---------|
| `TOTAL AMOUNT` | Total revenue across all products |
| `TOTAL BOXES` | Total boxes shipped |
| `TOTAL COSTS` | Total cost of goods |
| `TOTAL PROFIT` | Net profit calculation |
| `PROFIT%` | Profit margin percentage |
| `SHIPMENT COUNT` | Total number of shipments |
| `AMOUNT PER BOX` | Revenue efficiency per box |
| `last year total amount` | Previous year revenue for YOY |
| `total boxes (last year)` | Previous year boxes for comparison |
| `12 MON VARIANCE TOTAL AMOUNT` | 12 month revenue variance CY vs PY |
| `total boxes (last year variance)` | Box shipment variance YOY |
| `% Within Top 6` | Each product's % contribution within top 6 |