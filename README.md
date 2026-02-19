# SwiftRoute Logistics Performance Dashboard (Power BI)

An end-to-end logistics analytics dashboard built in **Power BI** to monitor **orders**, **on-time delivery**, **CSAT**, **hub capacity**, **driver performance**, and **vehicle status**.

## 🔎 Overview
This project provides operational visibility for a logistics company by tracking key KPIs and enabling drill-down analysis across drivers, hubs, and vehicles.

## ✅ KPIs
- Total Orders
- On-Time Delivery Rate
- Customer Satisfaction (CSAT)
- Average Delivery Time (Hours)
- Hubs Capacity vs Orders
- Drivers with Most Delays
- Active vs Maintenance Vehicles

## 🧠 Data Model
Star-schema style model with a central fact table (Orders) and supporting dimensions (Drivers, Hubs, Vehicles, Date).

## 🖼 Screenshots
| Overview | Drivers |
|---|---|
|<img width="1352" height="791" alt="home" src="https://github.com/user-attachments/assets/ce8a6d35-0405-449a-bf17-45a660e2460c" /> | <img width="1349" height="787" alt="drivers" src="https://github.com/user-attachments/assets/065875ee-6cd8-4931-87b9-d20ff839dba8" />) |

| Hubs | Vehicles |
|---|---|
|<img width="1345" height="787" alt="hubs" src="https://github.com/user-attachments/assets/4408d1e9-f935-4d07-8f94-a3e69c4a2876" /> | <img width="1343" height="786" alt="vehicles" src="https://github.com/user-attachments/assets/258d38ef-84af-40c7-a016-55638ae6a23a" /> |

## 🛠 Tools
- Power BI
- DAX
- Data Modeling

## 📁 Files
- **PBIX:** `report/SwiftRoute_Logistics_Dashboard.pbix`
- **PDF Export:** `exports/pdf/SwiftRoute_Dashboard.pdf`

## 🚀 How to Use
1. Download the `.pbix` file from the `report/` folder
2. Open in Power BI Desktop
3. Interact with slicers (Year/Month/Driver/Measure)

## 📌 Notes
If you use your own dataset, update Power Query connections and refresh the model.
