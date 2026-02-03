# Fleet-Safety-Risk-Analysis
This project analyzes large-scale truck telematics data to identify high-risk drivers, unsafe vehicle patterns, and geographic accident hotspots. The objective is to turn raw fleet data into actionable safety insights that help reduce risk and improve operational decision-making.

❓ Problem Statement
Commercial trucking fleets generate massive volumes of sensor and GPS data. The challenge is to answer key safety questions:
Which drivers exceed a critical safety risk threshold?
What unsafe driving behaviors are most common?
Do certain truck models contribute disproportionately to safety risk?
Where are the geographic hotspots with the highest concentration of incidents?

🛠 Tech Stack
Tool	Purpose
Hadoop (HDFS)	- Distributed storage for large-scale telematics data 
Hive - SQL-based querying and data processing on Hadoop 
Tableau -	Interactive dashboards and visualization

📊 Key Analysis
🚦 Driver Risk Assessment
Identified high-risk drivers (risk factor ≥ 7.0)

Analyzed dominant unsafe behaviors such as:
Unsafe following distance
Overspeeding
Lane departures
Found that risk does not decrease with experience, emphasizing behavior-focused safety programs

🚚 Vehicle Model Risk
Determined that risk is model-specific, not purely mileage-based
Highlighted certain truck models with elevated safety event rates
Suggested targeted maintenance and inspections for high-risk models

🌎 Geographic Risk Analysis
Performed geospatial analysis to locate accident hotspots
Identified high-risk cities and major freight corridors with concentrated incidents
Showed that a small number of locations account for a large share of safety events

💡 Recommendations

Implement targeted retraining for drivers exceeding risk thresholds
Use behavior-specific coaching instead of one-size-fits-all training
Increase preventive maintenance frequency for high-risk truck models
Deploy geo-fenced safety alerts and adjust routes in high-risk areas

📈 Impact

This project demonstrates how big data technologies can transform fleet telematics into practical safety strategies. The approach helps organizations:
✔ Reduce dangerous driving events
✔ Prioritize high-impact safety interventions
✔ Optimize fleet operations using data-driven insights
