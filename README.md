# 🌦️ Weather Data ETL Pipeline with Python, BigQuery & Power BI

This project demonstrates a complete data engineering pipeline for collecting, processing, and visualizing real-time weather data using modern tools and cloud services.

## 📌 Overview

- 📡 **Source:** OpenWeatherMap API  
- 🔄 **ETL Process:** Python for data extraction and transformation  
- ☁️ **Cloud Storage:** Google BigQuery (dataset: `etl_clima`)  
- 📊 **Visualization:** Interactive dashboard built in Power BI

## 📁 Files included

- `etl_clima.ipynb` → Python notebook with the full ETL pipeline  
- `dashboard.pbix` → Power BI dashboard with geolocation-based visualizations  
- `img/dashboard_preview.png` → Screenshot of the final dashboard

## 🌍 Dashboard Preview

![Weather Dashboard](img/dashboard_preview.png)

This interactive map shows current weather conditions (temperature, humidity, and description) for selected Colombian cities. The data is refreshed directly from a public API and loaded into Google BigQuery for easy querying and visualization.

## ⚙️ Tech Stack

- Python (requests, pandas)
- Google Cloud (BigQuery)
- Power BI
- OpenWeatherMap API

## 🚀 Future Improvements

- Schedule automated data ingestion with Airflow
- Append historical data for time series analysis
- Publish dashboard online using Power BI Service

## 👨‍💻 Author

**Ricardo Molina Gómez**  
[LinkedIn](https://www.linkedin.com/in/ricardomolinagomez)
