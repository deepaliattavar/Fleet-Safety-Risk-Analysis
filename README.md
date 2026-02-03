# Fleet-Safety-Risk-Analysis
This project analyzes large-scale truck telematics data to identify high-risk drivers, unsafe vehicle patterns, and geographic accident hotspots. The objective is to turn raw fleet data into actionable safety insights that help reduce risk and improve operational decision-making.

## Objective

- Identify drivers exceeding a defined safety risk threshold  
- Detect the most common unsafe driving behaviors  
- Evaluate risk patterns across different truck models  
- Pinpoint geographic areas with concentrated safety incidents  
- Generate data-backed recommendations for interventions

---
## Key Analysis

### Driver Risk Assessment
- Flagged drivers with **risk factor ≥ 7.0**
- Analyzed frequent unsafe behaviors:
  - Unsafe following distance  
  - Lane departures  
  - Overspeeding
- Found that driver risk does **not decrease with experience**, suggesting behavior-specific interventions

### Vehicle Model Risk
- Identified specific truck models with consistently higher risk
- Observed that risk was **not strongly correlated with mileage**, indicating model or maintenance differences

### Geographic Risk Analysis
- Performed geospatial analysis to uncover **incident hotspots**
- Found that a small number of cities and freight corridors account for many dangerous events

---
## 🛠 Tech Stack

- **Hadoop (HDFS)** – Distributed storage for large telematics datasets  
- **Hive** – SQL-based querying and analysis on Hadoop  
- **Tableau** – Data visualization and dashboards  

---

## Impact

This project demonstrates how big data frameworks can turn raw telematics into practical safety strategies. The insights guide fleet managers to focus resources on the highest-impact drivers, vehicles, and routes.

---
