# 📦 Last-Mile Operational Efficiency Dashboard
### A Diagnostic Analysis for Logistics Portfolio
<img width="1103" height="1042" alt="Screenshot 2025-09-29 030530" src="https://github.com/user-attachments/assets/b6a642bc-c05c-49b0-9c78-37addf8cb809" />

[![Tableau Public Link](https://img.shields.io/badge/View%20Live%20Dashboard-Tableau%20Public-blue?style=flat&logo=tableau)](https://public.tableau.com/app/profile/siri.yellu/viz/LogisticsOptimizationDashboard/Dashboard1?publish=yes)

## 📌 Project Goal

The primary objective of this project is to use **Tableau** and **Python** to perform a diagnostic analysis of a last-mile delivery network. The goal is to isolate assets, identify the root cause of systemic delays, and provide **actionable recommendations** for improving On-Time Delivery (OTD) performance.

## 📊 Key Findings & Business Impact

This analysis revealed significant operational failures requiring immediate attention:

* **Critical Underperformance:** The overall OTD Rate for the fleet is a low **43.40%**.
* **Asset Failure Diagnosis:** Filtering isolated the single lowest performer, **Truck\_10** (near 0% OTD), and definitively diagnosed its primary delay cause as **Mechanical Failure**.
* **Actionable Recommendation:** Immediate scheduling of preventative maintenance for Truck\_10 and auditing of driver logging procedures are necessary to correct the largest source of internal and unlogged delays.

## 🛠 Advanced Technical Skills

This project moves beyond standard dashboarding by demonstrating a **full-stack analytical pipeline:**

| Feature | Tool / Technique | Skill Demonstrated |
| :--- | :--- | :--- |
| **Hybrid Analytics** | Python (Pandas) | Calculated and injected a **Predicted Risk Score** for each delivery into the dataset. |
| **Geospatial Analysis** | Tableau Clustering | Grouped delivery locations into **performance clusters** based on risk and delay metrics. |
| **Advanced KPI** | LOD Expressions & Parameters | Calculated **OTD Variance** against an interactive **$90\%$ Goal Target** set by a parameter. |
| **Diagnostic Filtering**| Dashboard Actions | Created **Set Actions** to link asset performance directly to root causes and geospatial failure zones. |
| **Presentation** | Dual-Axis Charting | Combined OTD Rate (Line) with Shipment Volume (Bar) for contextual trend analysis. |

## 🔗 Live Dashboard Link

View the full interactive visualization here:

[Logistics Optimization Dashboard](https://public.tableau.com/app/profile/siri.yellu/viz/LogisticsOptimizationDashboard/Dashboard1?publish=yes)
