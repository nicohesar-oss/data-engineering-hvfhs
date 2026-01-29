# data-engineering-hvfhs
ETL en PySpark para procesamiento de datos HVFHS NYC TLC usando arquitectura Bronze / Silver / Gold
# HVFHS Data Engineering Pipeline (NYC TLC)

#Descripción
Este proyecto implementa un pipeline de ingeniería de datos utilizando una arquitectura Medallion (Bronze, Silver, Gold) sobre el dataset HVFHS de NYC TLC.

El objetivo es construir capas de datos estructuradas y optimizadas para análisis y consumo por herramientas de Business Intelligence (BI).

---

#Arquitectura
Arquitectura Medallion:

- **Bronze:** Ingesta de datos crudos en formato Parquet desde NYC TLC
- **Silver:** Limpieza, tipificación y estandarización de datos
- **Gold:** Agregaciones orientadas a KPIs y dashboards

---
 #Tecnologías
- Apache Spark (Databricks)
- Python (PySpark)
- Unity Catalog (Volumes)
- Parquet
- GitHub

---

#Estructura del proyecto
notebooks/
├── 01_bronze.ipynb
├── 02_silver.ipynb
└── 03_gold.ipynb
architecture/
└── arquitectura_medallion.png

---

#KPIs Generados
- Total de viajes por día
- Ingresos diarios
- Métricas por zona de recogida
- Resumen financiero global

---

#Ejecución
1. Ejecutar el notebook Bronze
2. Ejecutar el notebook Silver
3. Ejecutar el notebook Gold

---

#Fuente de datos
archivo High Volume For-Hire Vehicle Trip Records para enero de
2025
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page


