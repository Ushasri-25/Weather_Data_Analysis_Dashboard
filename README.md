## 🌦️  Weather Data Analysis

A multi-year, multi-state meteorological dataset exploring temperature, rainfall, humidity & wind patterns across India's four seasons.
--------------------------------------------------------
![dashboard_page-0001](https://github.com/user-attachments/assets/e982c98a-1749-4ef3-ab23-e9868a9a4856)
----------------------------------------------------------------
 ## 📖 About The Project
This project delivers an end-to-end weather data analysis covering 80 observations across multiple Indian states over a four-year period (2020–2023). The analysis focuses on temperature trends, rainfall patterns, humidity levels, and seasonal variations — presented through interactive dashboards, pivot tables, and visualizations within a single Excel workbook.

----------------------------
## 📊 Dataset Overview

| Attribute | Detail |
|:----------|:-------|
| **Records** | 80 observations |
| **Time Range** | January 2020 – December 2023 |
| **Regions** | Kerala, Rajasthan, Assam, Maharashtra, West Bengal, Tamil Nadu, and more |
| **Seasons** | Winter · Spring · Summer · Autumn |

------------------------------
### Features

| # | Column | Type | Description |
|:-:|--------|:----:|-------------|
| 1 | `Date` | Date | Observation date |
| 2 | `Month` | Text | Calendar month |
| 3 | `Season` | Text | Seasonal classification |
| 4 | `State` | Text | Indian state |
| 5 | `Avg Temp (°C)` | Numeric | Average temperature |
| 6 | `Max Temp (°C)` | Numeric | Maximum recorded temperature |
| 7 | `Min Temp (°C)` | Numeric | Minimum recorded temperature |
| 8 | `Rainfall (mm)` | Numeric | Rainfall measurement |
| 9 | `Humidity (%)` | Numeric | Relative humidity |
| 10 | `Wind Speed (km/h)` | Numeric | Wind speed |
| 11 | `Total Rainfall (mm)` | Numeric | Cumulative rainfall |
| 12 | `Avg Rainfall (mm)` | Numeric | Average rainfall |
| 13 | `Rainy Days` | Numeric | Count of rainy days |
--------------------------------------------

## 📑 Workbook Structure

WEATHER_DATA_ANALYSIS.xlsx
│
├── 📋 MAIN DATA         →  Raw dataset (80 records × 13 features)
├── 📊 DASHBOARD         →  Interactive visual dashboard
├── 📈 PIVOT TABLE       →  Monthly & seasonal aggregations
├── 🌡️ TEMPERATURE       →  Temperature trend analysis & charts
├── 💧 HUMIDITY          →  Humidity distribution & insights
├── 🌤️ WEATHER           →  Overall weather pattern analysis
└── 🌧️ RAINFALL          →  Rainfall distribution & regional trends
----------------------------------------------

## 🔍 Key Insights & Analyses
-----------------------------------

- **📅 Monthly Temperature Trends** — Aggregated average temperatures across all months revealing peak heat in June and lows in January
- **🍂 Seasonal Distribution** — Balanced dataset: Winter (21), Summer (20), Autumn (20), Spring (19) records
- **🗺️ State-wise Comparisons** — Cross-state analysis of temperature, humidity, and rainfall patterns
- **🌧️ Rainfall Patterns** — Monsoon impact analysis with Kerala recording the highest total rainfall (530 mm)
- **💧 Humidity Correlations** — Relationship between humidity, rainfall, and coastal vs. inland states
------------------------------------------

## 🚀 Getting Started

### Usage

```bash
# Clone the repository
git clone https://github.com/<your-username>/weather-data-analysis.git

# Navigate to the project
cd weather-data-analysis
```
1. Open `WEATHER_DATA_ANALYSIS.xlsx` in Excel
2. Start with the **DASHBOARD** sheet for a high-level overview
3. Use **slicers and filters** to drill down by state, season, or month
4. Explore individual analysis sheets (Temperature, Humidity, Rainfall) for detailed insights

   --------------------------
 ## 🛠️ Built With

| Tool | Purpose |
|:-----|:--------|
| **Microsoft Excel** | Data cleaning, pivot tables, charts, dashboard |
| **Pivot Tables** | Aggregation and cross-tabulation |
| **Excel Charts** | Data visualization |
| **Slicers** | Interactive filtering |

---------------------------

## 🤝 Contributing

Contributions are welcome! If you'd like to enhance the analysis or add new visualizations:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-analysis`)
3. Commit your changes (`git commit -m 'Add new analysis'`)
4. Push to the branch (`git push origin feature/new-analysis`)
5. Open a Pull Request

   ----------------------------
⭐ **If you found this project useful, please give it a star!** ⭐


----------------------------------
