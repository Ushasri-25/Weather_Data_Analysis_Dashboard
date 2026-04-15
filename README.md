## 🌦️  Weather Data Analysis

A multi-year, multi-state meteorological dataset exploring temperature, rainfall, humidity & wind patterns across India's four seasons.

--------------------------------------------------------
 ## 📖 About The Project
This project delivers an end-to-end weather data analysis covering 80 observations across multiple Indian states over a four-year period (2020–2023). The analysis focuses on temperature trends, rainfall patterns, humidity levels, and seasonal variations — presented through interactive dashboards, pivot tables, and visualizations within a single Excel workbook.

----------------------------
[Weather_Data_Analysis_Dashboard.pdf](https://github.com/user-attachments/files/26758517/Weather_Data_Analysis_Dashboard.pdf)

-------------------------------------------------------------
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

----------------------------------
# 📑 Workbook Structure

```
WEATHER_DATA_ANALYSIS.xlsx
EATHER__DATA_ANALYSIS.xlsx
│
├── 📋 MAIN DATA        →  Primary dataset  (80 rows × 13 columns)
├── 📊 DASH BOARD       →  Visual dashboard with charts & KPI cards
├── 🔢 PIVOT TABLE      →  Monthly & seasonal aggregation summaries
├── 🌡️  TEMPERATURE     →  Deep-dive: temperature metrics & trends
├── 💧 HUMIDITY         →  Deep-dive: humidity metrics & trends
├── 🌤️  WEATHER         →  Combined multi-variable pattern analysis
└── 🌧️  RAINFALL        →  Deep-dive: rainfall metrics & trends
```

## 🔍 Key Insights & Analyses
-----------------------------------

- **📅 Monthly Temperature Trends** — Aggregated average temperatures across all months revealing peak heat in June and lows in January
- **🍂 Seasonal Distribution** — Balanced dataset: Winter (21), Summer (20), Autumn (20), Spring (19) records
- **🗺️ State-wise Comparisons** — Cross-state analysis of temperature, humidity, and rainfall patterns
- **🌧️ Rainfall Patterns** — Monsoon impact analysis with Kerala recording the highest total rainfall (530 mm)
- **💧 Humidity Correlations** — Relationship between humidity, rainfall, and coastal vs. inland states
------------------------------------------

### 🌡️ Temperature 
| KPI | Value |
|-----|-------|
| 📈 Average Temperature | **26.1 °C** |
| 🔥 Highest Ever Recorded | **42.0 °C** — Rajasthan, May 2022 |
| 🥶 Lowest Ever Recorded | **7.0 °C** — Punjab, Jan 2023 |
| ☀️ Hottest Season (avg) | **Summer — 30.5 °C** |
| ❄️ Coldest Season (avg) | **Winter — 20.2 °C** |
| 🏆 Hottest State (avg) | **Tamil Nadu — 29.3 °C** |
| 🧊 Coolest State (avg) | **Punjab — 18.0 °C** |

-------------------------------

### 🌧️ Rainfall 
| KPI | Value |
|-----|-------|
| 💧 Average Rainfall | **55.9 mm** |
| ⛈️ Peak Single Event | **177.4 mm** — Kerala, Oct 2024 |
| 🏜️ Minimum Recorded | **4.0 mm** — Rajasthan, Feb 2020 |
| 🌊 Wettest Season (avg) | **Summer — 104.6 mm** |
| 🌵 Driest Season (avg) | **Winter — 24.4 mm** |
| 🌴 Wettest State (avg) | **Kerala — 102.3 mm** |
| 🏖️ Driest State (avg) | **Rajasthan — 6.7 mm** |

--------------------------
## 📈 Seasonal Breakdown

| Season | Obs | Avg Temp | Avg Rainfall | Avg Humidity | Avg Wind |
|--------|:---:|:--------:|:-----------:|:------------:|:--------:|
| ☀️ Summer | 20 | 30.5 °C | 104.6 mm | 75.5 % | 18.8 km/h |
| 🍂 Autumn | 20 | 25.2 °C | 64.4 mm | 64.9 % | 17.7 km/h |
| 🌸 Spring | 19 | 28.8 °C | 30.4 mm | 55.8 % | 17.9 km/h |
| ❄️ Winter | 21 | 20.2 °C | 24.4 mm | 59.7 % | 18.3 km/h |

---------------------------------

## 🗺️ State-wise Profile

| State | Obs | Avg Temp | Avg Rainfall | Avg Humidity | Avg Wind |
|-------|:---:|:--------:|:-----------:|:------------:|:--------:|
| 🌴 Kerala | 10 | 26.3 °C | 102.3 mm | 78.1 % | 17.7 km/h |
| 🌿 Assam | 9 | 22.5 °C | 74.7 mm | 73.0 % | 19.4 km/h |
| 🎭 Tamil Nadu | 9 | 29.3 °C | 62.8 mm | 66.1 % | 18.4 km/h |
| 🌊 Odisha | 8 | 28.4 °C | 62.0 mm | 68.1 % | 17.5 km/h |
| 🐯 West Bengal | 8 | 26.1 °C | 56.9 mm | 65.1 % | 18.6 km/h |
| 🕌 Uttar Pradesh | 6 | 24.3 °C | 53.2 mm | 61.0 % | 15.0 km/h |
| 🌆 Maharashtra | 7 | 28.3 °C | 51.4 mm | 62.7 % | 17.5 km/h |
| 🏰 Karnataka | 7 | 25.7 °C | 47.2 mm | 61.7 % | 20.4 km/h |
| 🦁 Gujarat | 7 | 26.4 °C | 21.3 mm | 49.0 % | 17.1 km/h |
| 🌾 Punjab | 3 | 18.0 °C | 20.3 mm | 61.7 % | 19.7 km/h |
| 🏜️ Rajasthan | 6 | 26.5 °C | 6.7 mm | 43.0 % | 18.9 km/h |

----------------------------
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
