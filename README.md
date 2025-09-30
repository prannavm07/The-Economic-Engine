# 🌐 The Economic Engine: A Global Economic Analysis Dashboard

A comprehensive Power BI dashboard analyzing the relationship between economic structure, GDP, and labor markets for countries worldwide from 1991 to 2022.

---

### 🛠️ Tech Stack

* **BI Tool**: Microsoft Power BI
* **ETL (Extract, Transform, Load)**: Power Query
* **Data Analysis & Modeling**: DAX (Data Analysis Expressions)

---

### 📊 Data Source

The project utilizes a single, consolidated CSV file containing longitudinal economic data for countries across the globe.

* **Source**: World Bank Open Data
* **Time Period**: 1991 - 2022
* **Key Columns**:
    * `Country Name`
    * `Year`
    * `GDP (in USD)`
    * `Unemployment Rate (%)`
    * `Employment Sector: Agriculture (%)`
    * `Employment Sector: Industry (%)`
    * `Employment Sector: Services (%)`

The data was cleaned and modeled within Power BI to handle missing values and create a star schema with a dedicated `Dates` table for robust time-intelligence calculations.

---

### ✨ Features & Highlights

#### **The Business Problem** 🤔

In a globalized world, understanding the drivers of economic growth and stability is crucial. Key questions for policymakers and analysts include: What defines a "developed" economy? How does the structure of a nation's labor force impact its economic output and employment stability?

#### **Goal of the Dashboard** 🎯

This dashboard aims to provide an interactive and intuitive tool to answer these questions. The primary goal is to visualize the story of economic modernization—the global shift from agriculture-based economies to industry and, ultimately, service-based economies—and analyze its correlation with GDP and unemployment.

#### **Walkthrough of Key Visuals** 🗺️

The dashboard is structured across three pages to guide the user from a high-level overview to a detailed analysis.

* **Page 1: Global Economic Overview**
    * **Dynamic KPIs**: At a glance, see the Total Global GDP, Average Unemployment Rate, and Dominant Employment Sector for any selected year.
    * **Interactive Map**: A color-saturated world map shows GDP distribution. Hovering over a country reveals a detailed tooltip with its key economic stats.
    * **Country Lookup**: An easy-to-use search slicer allows recruiters and users to instantly pull up data for any country of interest.

* **Page 2: Structural Shift Analysis**
    * **Hero Scatter Plot**: The centerpiece of the analysis, this chart plots `GDP` vs. `Services %`, with `Unemployment Rate` as the bubble size. It visually confirms the strong correlation between a robust service sector and a high GDP.
    * **100% Stacked Area Chart**: This visual clearly shows the 30-year global trend of the agricultural sector shrinking while the service sector expands to become the dominant source of employment.
    * **Top & Bottom 10 Tables**: Dynamically filtered tables provide a clear, ranked view of the highest and lowest-performing economies by GDP for the selected year.

* **Page 3: Country Deep Dive**
    * **Drill-Through Functionality**: Users can right-click any country on the main pages and "drill through" to this detailed report.
    * **Economic Journey Chart**: A combination line and column chart shows the specific country's GDP trend over time, overlaid on its changing economic structure.

#### **Business Impact and Highlights** 💡

* **Key Insight**: The dashboard successfully demonstrates that a larger service sector is a primary characteristic of high-GDP nations.
* **DAX Proficiency**: The project showcases advanced analytical skills through the creation of custom DAX measures like `GDP Year-over-Year Growth %` and calculated columns for dynamic segmentation (`Economic Tier`).
* **Interactive Storytelling**: The use of drill-through, dynamic titles, and cross-filtering across three distinct pages demonstrates an ability to build a comprehensive and user-friendly analytical tool, not just a static report.

---

### 📸 Screenshots/Demos

*Add your screenshots here to bring the project to life!*

**Page 1: The Global Overview**
`[Your Screenshot Here]`

**Page 2: In-Depth Analysis Page with Scatter Plot**
`[Your Screenshot Here]`

**Page 3: Country Deep Dive Drill-Through**
`[Your Screenshot Here]`
