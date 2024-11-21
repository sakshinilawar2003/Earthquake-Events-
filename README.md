# Earthquake Events Data Engineering Project with Microsoft Fabric  

## Project Overview  
This project demonstrates the creation of an end-to-end data engineering and analysis pipeline utilizing **Microsoft Fabric** capabilities, including **Data Factory**, **Data Engineering**, and **Power BI**. The pipeline ingests earthquake event data from the USGS API, processes it through various stages (Bronze, Silver, and Gold layers), and generates business-ready datasets for analytical insights.  

## Technologies Used  
- **Python**  
- **PySpark**  
- **Microsoft Fabric**  
  - Data Engineering  
  - Data Factory  
  - Power BI  

---

## Project Workflow  

1. **Data Ingestion (Bronze Layer)**  
   - Ingest raw earthquake data from the USGS API.  
   - Minimal processing is performed to preserve the data's original format.  
   - Stores foundational data for further refinement.  

2. **Data Transformation (Silver Layer)**  
   - Clean, transform, and consolidate data from the Bronze layer.  
   - Prepares the data for advanced analytical processing.  

3. **Data Refinement (Gold Layer)**  
   - Refines and optimizes data for high-value insights.  
   - Produces business-ready datasets tailored for reporting and visualization.  

4. **Visualization and Analysis**  
   - Create interactive dashboards and reports in Power BI.  

---

## Data Attribute Definitions  

| **Attribute**        | **Description**                                                              | **Type**         |  
|-----------------------|------------------------------------------------------------------------------|------------------|  
| `id`                 | Unique identifier for each earthquake event record.                         | String           |  
| `latitude`           | Latitude of the earthquake event.                                           | Double           |  
| `longitude`          | Longitude of the earthquake event.                                          | Double           |  
| `elevation`          | Elevation at which the event occurred (in meters).                         | Double           |  
| `title`              | Title or name of the earthquake event.                                      | String           |  
| `place_description`  | Description of the event location.                                          | String           |  
| `sig`                | Significance score of the earthquake event.                                 | Bigint           |  
| `mag`                | Magnitude of the earthquake.                                                | Double           |  
| `magType`            | Magnitude scale type used for the earthquake measurement.                   | String           |  
| `time`               | Timestamp of the event occurrence.                                          | Timestamp        |  
| `updated`            | Timestamp of the last update to the event record.                          | Timestamp        |  

---

## Prerequisites  

To complete this project, you will need:  
1. **Microsoft Fabric Account**  
   - Ensure access to Microsoft Fabric.  
   - Admin access is recommended.  

2. **Technical Skills**  
   - Familiarity with **Python**, **PySpark**, and data engineering concepts.  
   - Basic knowledge of Power BI for creating dashboards and reports.  

---

## Getting Started  

1. Download the project notebooks from the repository.  
2. Follow the step-by-step guidance provided in the YouTube tutorial for setup and execution.  
3. Ensure all dependencies and prerequisites are configured before proceeding.  

---

## Repository Contents  

| **File/Notebook**                          | **Description**                                                                                   |  
|--------------------------------------------|---------------------------------------------------------------------------------------------------|  
| **Worldwide Earthquake Events API - Bronze Layer Processing** | Notebook for ingesting raw earthquake data from the USGS API and storing it in the Bronze layer. |  
| **Worldwide Earthquake Events API - Silver Layer Processing** | Notebook for cleaning, transforming, and consolidating Bronze layer data into the Silver layer.  |  
| **Worldwide Earthquake Events API - Gold Layer Processing**   | Notebook for refining and optimizing Silver layer data into business-ready datasets (Gold layer).|  

---

## Key Outputs  

- **Raw Data**: Ingested data stored in the Bronze layer.  
- **Transformed Data**: Cleaned and structured data in the Silver layer.  
- **Business-Ready Data**: Optimized datasets for analytics in the Gold layer.  
- **Dashboards**: Interactive reports and visualizations in Power BI.  



