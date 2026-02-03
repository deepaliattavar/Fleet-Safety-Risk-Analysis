# Fleet-Safety-Risk-Analysis
This project analyzes large-scale truck telematics data to identify high-risk drivers, unsafe vehicle patterns, and geographic accident hotspots. The goal is to support data-driven decisions that improve fleet safety and reduce operational risk.

🔍 Problem Statement
Commercial trucking fleets generate massive amounts of sensor and location data. The challenge is to determine:
Which drivers exceed a critical risk threshold
What unsafe behaviors are most common
Whether certain truck models contribute to higher risk
Where geographic risk hotspots exist

🛠 Tech Stack
Hadoop (HDFS) – Distributed storage for large-scale telematics data
Hive – SQL-based querying on big data
Tableau – Data visualization and dashboarding

📊 Key Analysis
Identified high-risk drivers (risk ≥ 7.0) and analyzed dominant unsafe behaviors such as unsafe following distance, overspeeding, and lane departures
Discovered that risk is model-specific, not just mileage-based, highlighting certain truck models with elevated safety events
Conducted geospatial risk analysis, revealing accident hotspots concentrated in specific cities and highway corridors
Demonstrated that risk does not decrease with driver experience, emphasizing the need for behavior-based interventions

💡 Recommendations
Implement targeted retraining programs for high-risk drivers
Introduce behavior-specific coaching instead of one-size-fits-all training
Increase preventive maintenance for high-risk truck models
Deploy geo-fenced alerts and route optimization in identified high-risk locations

📈 Outcome
This project shows how big data tools can transform raw fleet telematics into actionable safety strategies, helping reduce dangerous events and improve overall transportation safety.
