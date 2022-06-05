# DW_Databricks
Sample code to create a data warehouse using [Databricks Community Edition](https://databricks.com/blog/2016/02/17/introducing-databricks-community-edition-apache-spark-for-all.html).

Jupyter notebooks:
- layer_raw - upload csv files to data lake in Databriks file system (DBFS)
- layer_trusted - save data in parquet format
- layer_refined - create data warehouse using delta tables
- analytics - data analysis using Apache Sparks
- configuration - settings shared by notebooks
- utilities - toolbox with basic functions
