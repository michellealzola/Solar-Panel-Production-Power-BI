# ☀️ Solar Panel Production Dashboard – Power BI Project

![Screenshot 2025-05-30 111037](https://github.com/user-attachments/assets/71c089a8-e3c6-4c89-9413-7d91cb58fa47)

## 📊 Project Overview

This Power BI report visualizes data from a solar panel production system to monitor performance metrics such as efficiency trends, power output, and production behaviors across weekdays, panel types, and assembly lines.

### 🔧 Objective

To transform raw production data into actionable insights that help the solar manufacturing team:
- Monitor average panel efficiency over time
- Compare outputs by panel design
- Evaluate operational behavior by weekday
- Identify trends to optimize production performance

---

## 📁 Datasets Used

This dashboard integrates the following structured CSV files:

| File Name            | Description |
|----------------------|-------------|
| `Dim_Date.csv`       | Contains calendar fields (Date, Day, Month, Weekday) |
| `Dim_Line.csv`       | Metadata for each assembly line |
| `Dim_Operator.csv`   | Operator info for future shift analysis |
| `Dim_Panel.csv`      | Panel specifications such as type, thickness, serial number |
| `Fact_Production.csv`| Main fact table with cycle time, efficiency, and power output |
| `solar_panel_production.pbix` | Power BI report file |

---

## 📈 Key Visuals

| Visual                | Purpose |
|-----------------------|---------|
| **Line Chart**        | Displays average panel efficiency (%) over time |
| **Matrix Table**      | Compares power output across panel types |
| **Weekday Slicer**    | Filters data by days of the week |
| **Cross-Highlighting**| Ensures interactive exploration across visuals |

---

## 💡 Why It Matters

Accurate monitoring of solar panel production leads to:
- **Faster root-cause analysis** during dips in efficiency
- **Better R&D feedback** based on panel design performance
- **Improved shift management** by analyzing weekday patterns
- **Smarter decision-making** via interactive dashboards

---

## 🚀 How to Use

1. Open `solar_panel_production.pbix` in Power BI Desktop
2. Load the CSV files as data sources
3. Explore the interactive report and adjust slicers to filter insights
4. Use the visuals to guide operational decisions

---

## 🔖 Tags

`Power BI` `Solar Energy` `Manufacturing Dashboard` `Data Visualization` `Production Analytics` `Efficiency Monitoring` `Business Intelligence` `Renewable Energy` `Python Portfolio`

---

## 📬 Get in Touch

Created by **Michelle Alzola**  
Visit [my blog]([https://python.michellealzoladesign.com](https://python.michellealzoladesign.com/maximizing-solar-panel-efficiency-power-bi-dashboard-for-production-monitoring/) for more tutorials and projects.

