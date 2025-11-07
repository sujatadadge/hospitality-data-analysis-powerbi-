# 🏨 Hospitality Domain Data Analytics Dashboard

## 🧾 Table of Contents
1. [Project Overview](#-project-overview)
2. [Tools & Techniques](#-tools--techniques)
3. [Key Insights & Features](#-key-insights--features)
4. [Dashboard Preview](#-dashboard-preview)
5. [Data Summary](#-data-summary)
6. [What I Learned](#-what-i-learned)
7. [Future Enhancements](#-future-enhancements)
8. [Repository Contents](#-repository-contents)
9. [How to View or Use](#-how-to-view-or-use)
10. [About the Author](#-about-the-author)

---

## 📌 Project Overview  
This Power BI project delivers a complete analytics solution for the **hospitality industry**, offering actionable insights into revenue, customer behaviour, and occupancy trends.  
The goal is to empower business owners, managers, and analysts to make data-driven decisions for growth and efficiency.

---

## 🛠 Tools & Techniques  
- **Power BI Desktop** – Data visualization and interactive dashboard creation  
- **DAX (Data Analysis Expressions)** – Advanced calculated measures and KPIs  
- **Excel / CSV** – Data cleaning and transformation  
- **Data Modelling** – Star schema with fact and dimension tables  
- **Power Query Editor** – Data preprocessing and transformation  

---

## 📊 Key Insights & Features  
- **Revenue Analysis** → Track total revenue, identify seasonal peaks, and compare monthly growth.  
- **Customer Segmentation** → Group guests by region, visit type (leisure/business), and booking patterns.  
- **Occupancy Dashboard** → Analyse room type performance and occupancy rates.  
- **KPI Cards** → Highlight business health metrics like ADR, RevPAR, and profit margin.  
- **Interactive Filters** → Filter data by date, region, room type, and guest category.  
- **Dynamic Visuals** → Intuitive charts that simplify trend understanding for decision-makers.  

---

## 📸 Dashboard Preview  
*(Add your own screenshots here for better presentation)*  

![Dashboard Screenshot 1](screenshots/dashboard_1.png)  
![Dashboard Screenshot 2](screenshots/dashboard_2.png)

---

## 🔍 Data Summary  
| Category | Description |
|-----------|-------------|
| **Domain** | Hospitality (Hotels & Resorts) |
| **Data Type** | Guest profiles, bookings, revenue, and occupancy data |
| **Time Period** | e.g., Jan 2023 – Dec 2023 |
| **Data Model** | Star Schema – Fact tables for Revenue & Bookings; Dimension tables for Guests, Rooms, and Time |
| **Key DAX Measures** | `TotalRevenue`, `RevPAR`, `AverageStay`, `TotalBookings` |

**Example DAX Formula:**  
```DAX
RevPAR = 
DIVIDE(
    SUM(FactRevenue[RevenueAmount]),
    SUM(FactOccupancy[OccupiedRooms]),
    BLANK()
)
💡 What I Learned

Building efficient data models in Power BI using relationships and hierarchies.

Writing DAX formulas for calculated columns and key business metrics.

Designing interactive dashboards with a professional look and easy usability.

Applying data storytelling principles to highlight business insights.

Presenting analytics projects in a way that’s portfolio-ready for internships.

🚀 Future Enhancements

Add real-time data refresh using Power BI Service and gateways.

Integrate Azure SQL or SharePoint as live data sources.

Include forecasting visuals for predictive trend analysis.

Create a mobile-friendly dashboard layout.

Automate daily email reports using Power Automate.

📂 Repository Contents
File / Folder	Description
Hospitality_Dashboard.pbix	Main Power BI project file
/data	(Optional) Cleaned or sample dataset files
/screenshots	Dashboard preview images
README.md	This documentation file
🧭 How to View or Use

Download the .pbix file from this repository.

Open it using Power BI Desktop.

Explore the visuals, filters, and metrics interactively.

(Optional) Connect your own dataset to reuse the dashboard structure.

👩‍💻 About the Author

Sujata Dadge
Aspiring Data Analyst passionate about transforming complex datasets into actionable insights. Skilled in Power BI, Python (NumPy, Pandas), and data storytelling.
Currently building projects in banking and hospitality analytics to enhance domain expertise and portfolio strength.
