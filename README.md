# 📊 Netflix Power BI Dashboard Project

An interactive data visualization dashboard created using **Power BI** to analyze global Netflix content. The analysis provides actionable insights into genre trends, content types, ratings, country contributions, and historical growth from **1925 to 2021**.

---

## 🧼 Data Cleaning & Preparation

The raw Netflix dataset was thoroughly cleaned using **Excel Power Query** before importing into Power BI.

### 🔧 Cleaning Steps Included:

- Removed duplicates and null rows
- Created new calculated columns:
  - `Main Genre`
  - `Main Country`
  - `Duration_Minutes`
- Filled blank fields with `Unknown` for consistency
- Standardized formats (split multiple genres/countries)
- Final cleaned data exported to Power BI

---

## 🧩 Dashboard Overview

### 🔍 1. Global Overview Dashboard

![Overview](https://github.com/OmkarGaurav121/Netflix_Powerbi_dashboard/blob/main/Overview%20dasdhboard.png)

**Purpose:** Snapshot of platform scale and content distribution.

**Key Visuals:**

- KPIs (Cards):  
  - Total Movies: **8803**
  - Total Genres: **36**
  - Total Ratings: **15**
  - Years Covered: **1925–2021**
  - Total Directors: **4525**
  - Countries Involved: **749**
- Top Genres Bar Chart
- Movie vs TV Show Donut Chart
- World Map by Show Count

📌 **Insight:** U.S. dominates production, and TV shows have gained a strong presence.

---

### 🎬 2. Content Analysis Dashboard

![Content Dashboard](https://github.com/OmkarGaurav121/Netflix_Powerbi_dashboard/blob/main/Content%20dashoard.png)

**Purpose:** Explore content by type, duration, and maturity rating.

**Key Visuals:**

- Bar Chart: Top genres by type
- Pie Chart: Top 5 content ratings (TV-MA, TV-14, etc.)
- Type vs Rating Relationship
- Average Duration per Genre

📌 **Insight:** Drama and Comedy dominate, and mature content is most common.

---

### 📈 3. Timeline Dashboard – Netflix Over Time

![Timeline](https://github.com/OmkarGaurav121/Netflix_Powerbi_dashboard/blob/main/Timeline%20dashboard.png)

**Purpose:** Analyze Netflix’s growth and genre evolution through the decades.

**Key Visuals:**

- Line Chart: Number of titles added per year
- Line Chart: Average duration trends over time
- Genre trends by release year
- Ratings distribution over time

📌 **Insight:** Explosive content growth began post-2010, especially in mature-rated content.

---

### 🌍 4. Country Trends & Production Insights

![Country Trends](https://github.com/OmkarGaurav121/Netflix_Powerbi_dashboard/blob/main/Country%20Trends.png)

**Purpose:** Compare regional content output and genre preferences.

**Key Visuals:**

- Treemap: Total content per country
- Line Graph: Country-wise content growth
- Stacked Bar: Genre preference by region
- Donut Chart: Share of countries in overall content

📌 **Insight:** While the U.S. is dominant, India and Japan show rapid recent growth.

---

## 📌 Project Highlights

- ✅ Data cleaned and structured using **Excel Power Query**
- ✅ Built 4 detailed dashboards with interlinked filters and slicers
- ✅ Dark-th
