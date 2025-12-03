# AirSight-Analytics-ETL-
A scalable, cloud-native data engineering pipeline built on AWS to ingest, clean, model, and analyze global air quality measurements from the OpenAQ dataset.
AirSight Analytics processes historical air quality data (CO, SO₂, PM2.5) and loads it into a Redshift-based data mart optimized for analytical workloads.
The pipeline ingests raw data from OpenAQ, performs validation + interpolation, applies quality checks, and surfaces insights for business analysts.

This project addresses complex analytical requirements such as:

Monthly 90th percentile CO and SO₂ pollution across global cities

Top 5 cities with highest daily PM2.5 levels

Top 10 cities by hourly PM2.5 and CO/SO₂ mean, median, mode
