# 🚑 Delayed Transfers of Care Dashboard (Power BI)

This repository showcases a complete Power BI analytics project built to study **NHS and Social Care delayed discharge data**. 
The aim is to highlight key patterns, performance issues, and operational inefficiencies across Local Authorities and Responsible Organisations in England.

---

## 🧭 Project Overview

This project uses the **Delayed Transfers of Care (DTOC)** dataset from NHS England (2018/19) to understand how discharge delays affect hospital capacity and patient flow.  
It demonstrates the full end-to-end process of data preparation, modelling, DAX calculation, and dashboard development in Power BI.

The dashboard provides an easy-to-navigate visual interface for exploring total delayed days, delay causes, and trends by organisation and region.

---

## 🎯 Project Objectives

- Measure **total delayed days** across NHS, Social Care, and Joint responsibilities.  
- Identify **seasonal and regional delay trends**.  
- Compare **Acute vs Non-Acute** delay patterns.  
- Build **interactive Power BI visuals** to improve transparency and decision-making.  

---

## 🧱 Folder Structure

```
 powerbi-projects/
│
└── delayed-transfers-of-care/
    ├── data/
    │   └── DTOC-England-Data_Set.xls               # Example dataset for demonstration
    │
    ├── report/
    │   └── delayed_transfers_report.pbix  # Power BI model file
    │
    ├── dashboards/
        ├── overview_dashboard.png
        ├── type_of_care_analysis.png
        ├── responsible_org_analysis.png
        └── reason_for_delay_analysis.png
    │
    └── README.md                           # Documentation (this file)
```

---

## 📊 Key Insights

- **Seasonal Variations:** Winter months showed the highest number of delayed days, indicating resource strain during peak hospital occupancy.  
- **NHS vs Social Care:** NHS-related delays formed the majority share, signalling areas for coordination improvements.  
- **Regional Focus:** Certain Local Authorities displayed recurring delays across multiple months.  
- **Operational Intelligence:** Provided the foundation for performance monitoring and improvement strategies.

---

## 🧠 Power BI Development Workflow

### 1️⃣ Data Preparation
- Imported monthly DTOC CSV datasets into Power BI.  
- Cleaned and standardised columns using **Power Query Editor**.  
- Consolidated multiple tables and removed duplicates.  

### 2️⃣ Data Modelling
- Designed a **star schema** for clean relationships between facts and dimensions.  
- Added DAX measures for custom KPIs:  

```DAX
Total Delayed Days = SUM('DTOC Data'[Total_Delayed_Days])
NHS Delayed Days = SUM('DTOC Data'[NHS_Delayed_Days])
Social Care Delayed Days = SUM('DTOC Data'[Social_Care_Delayed_Days])
Joint Delayed Days = SUM('DTOC Data'[Joint_Delayed_Days])
```

### 3️⃣ Visual Design
- Built **KPI cards** for summary metrics.  
- Designed **bar charts** for organisation-level analysis.  
- Created **line charts** for monthly trends.  
- Added **slicers and filters** for Year, Month, and Organisation Type.  

### 4️⃣ Formatting & Branding
- Applied a consistent **NHS-inspired theme**.  
- Used uniform colour coding and typography.  
- Included descriptive titles, tooltips, and clean layout spacing.  

### 5️⃣ Deployment & Showcase
- Published report to Power BI Service for sharing.  
- Exported visuals and created an HTML embed file for GitHub Pages.  

---

## 🧩 Tools & Technologies Used

- **Power BI Desktop** – Data transformation, modelling, visualisation  
- **Power Query Editor** – Data cleaning and preprocessing  
- **DAX (Data Analysis Expressions)** – KPI and calculated measures  
- **Excel/CSV** – Data source files for import  
- **GitHub Pages** – Hosting of embedded visualisations  

---

## 💼 Skills Demonstrated

- Data storytelling and visual analytics  
- ETL (Extract, Transform, Load) in Power BI  
- DAX-based measure creation and analysis  
- Dashboard layout design and interactivity  
- Clean documentation and GitHub project presentation  

---

## 🏁 Outcome

The Power BI dashboard successfully visualises key DTOC metrics and patterns, offering actionable insights to healthcare planners and analysts.  
It illustrates how effective Power BI modelling and design can transform raw NHS data into **clear, interactive, and decision-ready intelligence**.

---

© 2025 **Sanjay Krishnan**  
Power BI | Data Analytics | Cloud & IT Professional
