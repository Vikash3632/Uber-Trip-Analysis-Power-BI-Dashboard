# 🚖 Uber-Trip-Analysis-Power-BI-Dashboard

A comprehensive Power BI project analyzing Uber trip data, designed to provide business insights into ride volume, fare trends, time patterns, location hotspots, and vehicle preferences.

## 📊 Project Overview

This Power BI report explores more than **100K Uber bookings** using interactive dashboards and well-modeled datasets. The goal is to uncover actionable insights related to booking behavior, time-based trends, and geographic patterns.

### 🔍 Key Features

- **Dynamic KPIs** for total bookings, revenue, average fare, trip time & distance
- - **Dynamic Measures** Total bookings,Total Booking Value,Total Trip distance to dynamically update the visualizations based By
  - Payment Type (Card, Cash, Wallet, etc.)
  - By Trip Type (Day/Night)
  - Dynamic Title – Update the chart title based on the selected measure.
  - Slicers – Add filters for Date, City, and other interactive filters for deeper analysis.
  - Tooltips – Show additional details like Average Booking Value or Trip Distance

- **Visuals by Payment Type, Trip Timing (Day/Night), and Vehicle Type**
- **Time Series Analysis** by Pickup Hour, Day of Week, and Hour-Day Heatmap
- **Location Analysis**: Most Frequent Pickup & Drop-off Points
- **Fully interactive dashboards** with slicers and filters for date and city

---

## 📁 File Structure

Uber-Trip-Analysis/
│
├── Uber Power BI Report.pbix # Main Power BI dashboard file
├── Uber Trip Details.xlsx # Ride-level transactional data
├── Location Table.xlsx # Location ID to name/city mapping
├── images/
│ ├── dashboard-overview.png # Overview page screenshot
│ ├── time-analysis.png # Time analysis visual
│ └── trip-details.png # Detailed table view
├── info.PNG # Data dictionary/explanation
└── README.md # This file

---

## 🧩 Data Model

The data model is structured in a star schema with the following tables:

### 🔹 Trip Details Table
Contains transactional trip data with:
- Pickup & drop-off timestamps
- Fare amount, trip distance, vehicle type
- Payment method, passenger count
- Pickup & drop-off location IDs

### 🔹 Location Table
Maps location IDs to:
- Location names (e.g., Times Sq, JFK Airport)
- City (for segmentation and filtering)

### 🔹 Calendar Table
Date-based table for time intelligence and slicer filtering.

### 🔹 Dynamic Measure Table
Used to create dynamic titles and parameterized visualizations.

---

## ⚙️ Skills Demonstrated

- 📐 **Data Modeling**: Relationships, star schema, normalization
- 💡 **DAX**: Custom measures, KPIs, dynamic titles
- 🧭 **Time Intelligence**: Hourly, daily, and weekly trends
- 🎨 **Dashboard Design**: UX-friendly layout and interactivity
- 🛠 **Power BI Features**: Slicers, drill-through, bookmarks, tooltips

---

## 📈 Dashboard Pages

1. **Overview Analysis**  
   KPIs, Payment Types, Trip Timing, Location-Based Metrics

2. **Time Analysis**  
   Hourly bookings, Day-of-week trends, Heatmaps

3. **Details**  
   Tabular data view for all individual trips

---

## 🗂 Data Source

- **Uber Trip Details.xlsx**  
  Synthetic trip data (Pickup/Drop-off, Fare, Distance, Vehicle)

- **Location Table.xlsx**  
  Mapping of location IDs to city and area names

- **Uber Power BI Report.pbix**  Uber Power BI Report.pdf
  Main Power BI Report

- **Uber Power BI Report.pdf**
 all Three dashborad pdf.

## 📌 Author

**Vikash Chaudhary**  
Aspiring Data Analyst | Certified in Data Analysis by Microsoft & LinkedIn | Skilled in Power BI, Excel, SQL & Python | Background in Data-Driven Lab Testing & Reporting
[LinkedIn](https://www.linkedin.com/in/vikash-chaudhary-12b27a1b4)
