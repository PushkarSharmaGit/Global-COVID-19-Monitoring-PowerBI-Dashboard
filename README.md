# 🦠 Global COVID-19 Monitoring Dashboard

![COVID19 Dashboard Preview](COVID19_Dashboard_Preview.png)

## 📌 Project Overview
An interactive Power BI dashboard built to monitor and analyze the global spread of COVID-19 across 200+ countries. The dashboard enables continent-wise and country-level drill-downs to track key epidemiological metrics and support data-driven insights.

---

## 🛠️ Tools Used
- **Microsoft Power BI** — Dashboard design and data visualization
- **Power Query** — Data cleaning and transformation
- **DAX (Data Analysis Expressions)** — Custom measures and KPI calculations
- **Dataset:** Worldometer COVID-19 Data (worldometer_data.csv)

---

## 📊 Dashboard Features

### KPI Cards
- Total Population: **6bn**
- Total Cases: **19M**
- Total Deaths: **712.99K**
- Total Recovered: **12.07M**
- Total New Cases: **7.92K**
- Total Serious/Critical: **65.19K**

### Visualizations
- **Clustered Bar Chart** — Total Cases by Country/Region (USA: 5M, Brazil: 2.9M, India: 2M, Russia: 0.9M)
- **Pie Chart** — Total Cases by Continent (North America: 30.88%, Asia: 24.47%, South America: 23.7%, Europe: 15.56%)
- **Area Chart** — Total Cases vs Total Recovered by Continent
- **Line and Clustered Column Chart** — New Cases and New Deaths comparison
- **Ribbon Chart** — Total Recovered by Continent
- **Continent Slicer** — Filter by Africa, Asia, Australia/Oceania, Europe, North America, South America
- **Country/Region Slicer** — Drill down to individual countries

---

## 🔍 Key Insights
- **USA** led globally with **5M total cases**, followed by Brazil (2.9M) and India (2.0M)
- **North America** had the highest share of total cases at **30.88%**, closely followed by Asia at **24.47%**
- Global total deaths reached **712.99K** with **65.19K serious/critical** cases
- **Asia** recorded the highest total recoveries among all continents
- Africa and Australia/Oceania had significantly lower case counts and near-zero recoveries in comparison

---

## 🧹 Data Preparation
- Cleaned and transformed raw Worldometer data using **Power Query**
- Handled missing values and standardized column formats
- Created custom **DAX measures** for KPI calculations including recovery rate and case distribution
- Converted population display units to Billions for cleaner card visuals

---

## 📁 Files in This Repository
| File | Description |
|------|-------------|
| `Global_COVID-19_Monitoring_Dashboard.pbix` | Power BI dashboard file |
| `worldometer_data.csv` | Raw dataset used for analysis |
| `COVID19_Dashboard_Preview.png` | Dashboard screenshot |
| `README.md` | Project documentation |

---

## 📬 Contact
**Pushkar Sharma**
- 📧 sharmapushkarmail@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/sharma-pushkar)
- 🐙 [GitHub](https://github.com/PushkarSharmaGit)
