# ☕ Colombian Coffee Export Dashboard (Power BI)

An end-to-end data analytics project that explores **Colombian coffee export dynamics** through an interactive Power BI dashboard built using the `.pbip` project structure for version control.

This project showcases a complete workflow: from raw Excel data to a structured data model and a fully interactive report.

---

## 📊 Project Overview

Colombia is one of the world's leading coffee exporters. This project analyzes export data to uncover:

* Export trends over time
* Key destination markets
* Port-level export distribution
* Patterns in volume and logistics

The main goal is to demonstrate how **raw operational data** can be transformed into **business insights** using Power BI. In addition, it is desired that you provide a report based on official information to assess the export capacity of Colombian coffee.

---

## 🏗️ Architecture & Workflow

This project follows a modern analytics workflow:

1. **Data Sources**

   * Excel files containing export records
   * Port location reference data

2. **Data Transformation (Power Query)**

   * Data cleaning and normalization
   * Column standardization
   * Handling missing values
   * Merging datasets (exports + port locations)

3. **Data Modeling**

   * Relational model between exports and location data
   * Optimized structure for analytics

4. **Visualization Layer (Power BI Report)**

   * Interactive dashboards
   * Filters and slicers
   * Aggregated KPIs

---

## 📂 Project Structure

```
ColombianCoffee-main/
│
├── ColombianCoffeeExportations.pbip   # Power BI project (Git-friendly)
│
├── ColombianCoffeeExportations.Report/
│   ├── definition/                    # Report definition (JSON)
│   ├── pages/                         # Dashboard pages
│   └── StaticResources/               # Themes and assets
│
├── *.xlsx                             # Data sources
│   ├── Exportaciones-2025-1.xlsx
│   ├── ExportacionesSource.xlsx
│   └── ports_location.xlsx
│
├── exportacionesPreview.png           # Dashboard preview
├── Background.png / .pptx             # Visual assets
│
└── README.md
```

---

## 📈 Dashboard Features

The Power BI report enables:

* 📦 Analysis of **export volumes**
* 🌎 Identification of **top export destinations**
* 🚢 Insights by **port of departure**
* 📅 Time-based trend analysis
* 🎯 Interactive filtering by key dimensions

---

## 🖼️ Dashboard Preview

![Dashboard Preview](exportacionesPreview.png)

---

## 📚 Data Source

The data used in this project comes from the official reports published by the
**Federación Nacional de Cafeteros de Colombia**.

* Source:
  https://federaciondecafeteros.org/wp/estadisticas-cafeteras/

These reports provide detailed statistics on coffee production, exports, and commercialization in Colombia.

The datasets included in this repository are derived and adapted from these official sources for analytical and educational purposes.

---

## ⚙️ How to Use

1. Clone the repository:

   ```
   git clone https://github.com/SantiOrtizQ/ColombianCoffee.git
   ```

2. Open the `.pbip` file in **Power BI Desktop**

3. If needed:

   * Update file paths to local Excel sources
   * Refresh the data model

4. Explore the report interactively

---

## 🧠 Key Learnings & Skills Demonstrated

* Power BI project structure using `.pbip` (version control friendly)
* Data transformation with **Power Query (M)**
* Data modeling and relationships
* Dashboard design and storytelling
* Working with real-world export datasets

---

## 🚀 Possible Improvements

* Automate data ingestion (e.g., API or database connection)
* Add advanced DAX measures (YoY growth, moving averages)
* Improve geospatial visualizations
* Deploy to Power BI Service

---

## 👤 Author

**Santiago Ortiz**
Engineering Physicist | Data Analytics | Data Engineering

GitHub:
https://github.com/SantiOrtizQ

---

## 📌 Notes

* This project uses local Excel files as data sources
* No sensitive information is included
* Designed for learning, portfolio, and demonstration purposes

---
