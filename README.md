# PlayStation Sales and Metadata Dashboard

**PS3 • PS4 • PS5**

## Project Description

This project delivers a **data-driven analysis of PlayStation game sales and metadata** across three console generations (PS3, PS4, PS5). It combines a structured dataset, an interactive business intelligence dashboard, and a detailed analytical report to evaluate commercial performance, regional dynamics, lifecycle trends, and content quality indicators.

<img width="1290" height="715" alt="Screenshot 2026-01-13 123700" src="https://github.com/user-attachments/assets/9300d4f5-9be4-456e-a526-bec18fdc71dd" />

The solution is designed to support:

* **Executive decision-making**
* **Strategic portfolio evaluation**
* **Business intelligence learning objectives**
* **Data analytics best practices**

---

## Business Context

The video game industry is highly competitive and lifecycle-driven. Understanding **sales performance by platform, region, and time**, alongside **quality indicators such as ratings and Metacritic scores**, is critical for optimizing release strategies, inventory planning, and long-term platform investments.

This project simulates a **real-world analytics scenario** where stakeholders require both:

* High-level KPIs for quick insights
* Granular drill-down analysis for operational and strategic decisions

---

## Project Objectives

* Consolidate PlayStation sales and metadata into a unified analytical dataset
* Design a scalable and BI-optimized data model
* Visualize key performance indicators (KPIs) for executive consumption
* Analyze regional and temporal sales patterns
* Assess relationships between content quality and commercial success
* Provide actionable insights and strategic recommendations

---

## Repository Structure

```
├── PlayStation Sales and Metadata Dashboard Report.docx
├── Dataset/
│   └── playstation_sales_metadata.csv
├── Dashboard/
│   └── PlayStation_Sales_Dashboard.pbix
├── README.md
```

---

## Dataset Overview

### Data Coverage

* **Platforms:** PS3, PS4, PS5
* **Time Range:** Multi-year historical data
* **Regions:**

  * North America
  * Japan
  * Other Global Regions

### Data Domains

* **Commercial Metrics**

  * Total Sales
  * Total Units Shipped
* **Regional Metrics**

  * NA Sales
  * JP Sales
  * Other Regional Sales
* **Quality Metrics**

  * Ratings
  * Metacritic Scores
* **Time Intelligence**

  * Year
  * Quarter
  * Month
  * Day

---

## Data Model & Design

The dataset is structured using a **star-schema-inspired model**, optimized for dashboard performance and analytical flexibility.

* **Fact Table**

  * Sales and shipment metrics at the game level
* **Dimension Tables**

  * Platform
  * Time
  * Region
  * Metadata (ratings, Metacritic scores)

This design ensures:

* Fast query performance
* Scalability for future data expansion
* Clear separation of metrics and descriptive attributes

---

## Dashboard Components

### KPI Section (Executive View)

The dashboard begins with KPI cards that summarize:

* Total global sales
* Total units shipped
* Average ratings
* Average Metacritic scores

These KPIs provide immediate insight into overall portfolio health.

### Analytical Visuals

* **Sales vs. Shipped Comparison**
  Evaluates sell-through efficiency and distribution effectiveness.
* **Regional Sales Distribution**
  Highlights market dominance and geographic contribution.
* **Year-over-Year Trends**
  Illustrates lifecycle performance across console generations.
* **Platform Comparison**
  Enables cross-generation performance analysis.

### Filters & Interactivity

* Platform slicers (PS3, PS4, PS5)
* Time hierarchy filters (Year → Quarter → Month → Day)
* Dynamic cross-filtering between visuals

---

## Key Insights Summary

* The PS4 generation represents the strongest historical sales performance
* North America is the primary revenue driver across all platforms
* Japan, while smaller in volume, remains strategically significant
* Sales decline post-2020 aligns with console transitions and dataset limitations
* Higher ratings and Metacritic scores generally correlate with stronger sales

---

## Technical Architecture

1. **Data Source**

   * Consolidated CSV dataset
2. **Data Processing**

   * Cleaning, normalization, aggregation
3. **Semantic Layer**

   * Measures, calculated KPIs, and time intelligence
4. **Visualization Layer**

   * Interactive BI dashboard with slicers and KPIs
5. **Reporting Layer**

   * Executive-focused analytical report (.docx)

---

## Roles & Responsibilities

* **Data Engineer**

  * Data ingestion, cleaning, and model optimization
* **BI Developer**

  * Dashboard design, KPI logic, and performance tuning
* **Data Analyst**

  * Insight generation and validation
* **Business Stakeholder**

  * Requirements definition and strategic alignment

---

## Assumptions & Limitations

* Dataset does not fully capture post-2020 PS5 digital sales
* Digital vs. physical sales are not separated
* External market factors (pricing, promotions) are not included
* Data represents historical trends rather than real-time performance

---

## Recommendations

* Maintain strategic focus on North America while localizing content for Japan
* Use quality metrics as early predictors of commercial performance
* Expand future datasets to include:

  * Digital vs. physical sales breakdown
  * PS5-era releases
  * Subscription-based revenue models

---

## Learning Outcomes

This project demonstrates:

* Data modeling for BI applications
* KPI-driven dashboard design
* Time-series and regional sales analysis
* Translating data insights into business recommendations
* End-to-end analytics workflow from data to executive reporting

---

## Conclusion

The PlayStation Sales and Metadata Dashboard provides a **comprehensive, scalable, and executive-ready analytics solution**. By integrating sales, regional, temporal, and quality metrics into a single analytical framework, the project supports informed decision-making and long-term portfolio optimization across console generations.

---


