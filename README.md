# Earthquake Data Engineering Project with Microsoft Fabric
Project Overview:
This project demonstrates how to build an end-to-end data engineering pipeline using Microsoft Fabric (Data Factory + Data Engineering).

The pipeline ingests real-time earthquake event data from the USGS API and processes it through Bronze, Silver, and Gold layers following the medallion architecture.

# Technologies Used:
Python, PySpark, Fabric (Data Engineering, Data Factory)

# Repository Contents:
Bronze Layer: Raw ingestion from USGS API, minimal transformations, landing zone.

Silver Layer: Cleaning, transforming, typing, and standardizing earthquake data.

Gold Layer: Business-ready curated datasets for analytics and reporting.

# Data Attribute Definitions:
latitude: Earthquake latitude (double)

longitude: Earthquake longitude (double)

elevation: Elevation in meters (double)

title: Event title or summary (string)

place_description: Description of the earthquake location (string)

sig: Significance score (bigint)

mag: Earthquake magnitude (double)

magType: Magnitude scale type (string)

time: Event timestamp (timestamp)

updated: Last update timestamp (timestamp)
