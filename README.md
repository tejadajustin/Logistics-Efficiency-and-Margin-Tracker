
# Logistics Efficiency and Margin Tracker

## Project Overview
An interactive, executive-facing dashboard built to evaluate macro-level supply chain performance. This project utilizes a  relational data model to expose the direct financial impact of regional delivery constraints on overall profit margins.

## Technical Architecture
* **ETL (Extract, Transform, Load):** Utilized Power Query to clean, shape, and format raw supply chain data.
* **Relational Data Modeling:** Constructed a star schema in Power Pivot, linking supply chain fact tables with dimensional  tables to ensure accurate filtering.
* **Calculation Engine:** Engineered custom DAX (Data Analysis Expressions) measures to dynamically process and aggregate performance metrics.
* **Data Visualization:** Designed a matte-style interface utilizing Top-N filtering and data-ink optimization.

## Core Logic & DAX Measures
The backend calculation engine relies on specific DAX logic to dynamically update visuals across all slicers. 

**Late Delivery Rate**
Late Delivery Rate % = DIVIDE([Late Orders], [Total Orders], 0)

## Final Dashboard Preview
<img width="2806" height="1280" alt="Recording 2026-08-16 192541" src="https://github.com/user-attachments/assets/da3a7ca8-20e5-4458-be59-b7e937473c50" />

