# 🏨 Hotel Sales Analysis Dashboard

An interactive Power BI dashboard for analyzing hotel revenue performance across property types, locations, age groups, and time periods.

---

## 📊 Dashboard Overview

![Hotel Sales Analysis Dashboard](./Screenshot_2026-03-12_235523.png)

The dashboard provides a comprehensive view of hotel sales data, enabling stakeholders to explore revenue trends and make data-driven decisions.

---

## ✨ Features

- **Revenue KPI Card** — Displays total revenue (1.43M) vs. goal with percentage achievement
- **Year Filter** — Toggle between 2022, 2023, and 2024 data with a range slider
- **Revenue by Location City** — Bar chart ranking cities by total revenue
- **Revenue by Age Group** — Grouped bar chart comparing spending across 18–25, 26–35, 36–50, and 50+ segments
- **Revenue by Month** — Line chart tracking monthly revenue trends throughout the year
- **Revenue by Property Type** — Pie chart breaking down revenue share across Apartments, Houses, Studios, and Villas

---

## 📁 Project Structure

```
hotel-sales-analysis/
│
├── data/
│   └── hotel_sales_data.csv       # Raw sales dataset
│
├── dashboard/
│   └── HotelSalesAnalysis.pbix    # Power BI dashboard file
│
├── screenshots/
│   └── dashboard_preview.png      # Dashboard screenshot
│
└── README.md
```

---

## 📈 Key Insights

| Metric | Value |
|--------|-------|
| Total Revenue (2024) | **5.01M** |
| Displayed Filtered Revenue | **1.43M** |
| Top Revenue City | **Edwardsville** (~20K) |
| Peak Revenue Month | **July** (467K) |
| Lowest Revenue Month | **April** (339K) |
| Top Property Type | **Apartment** (28.6%) |
| Top Age Group | **18–25** (1.29M) |

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard creation and visualization
- **Microsoft Excel / CSV** — Data source
- **DAX** — Calculated measures and KPIs

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/prajwal537892/hotel-sales-analysis.git
   cd hotel-sales-analysis
   ```

2. **Open the dashboard**
   - Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) if not already installed
   - Open `dashboard/HotelSalesAnalysis.pbix`

3. **Connect your data** *(if using your own dataset)*
   - Go to **Home → Transform Data**
   - Update the data source path to point to your CSV file

---

## 📋 Data Fields

| Column | Description |
|--------|-------------|
| `Location_City` | City where the property is located |
| `Property_Type` | Type of property (Apartment, House, Studio, Villa) |
| `Age_Group` | Customer age group (18–25, 26–35, 36–50, 50+) |
| `Revenue` | Total revenue generated |
| `No_of_Bedrooms` | Number of bedrooms in the property |
| `Year` | Year of the booking |
| `Month` | Month of the booking |

## 📬 Contact

For questions or feedback, feel free to open an issue or reach out via [GitHub Discussions](https://github.com/your-username/hotel-sales-analysis/discussions).
