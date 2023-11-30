# US_healthcare_data_pipeline
Developing a PySpark Data Pipeline Solution with Cloud and Big Data Integration

## About
In this project we work on raw data on US prescribers that we will preprocess into a data warehouse, then transform this data to provide two data marts.

## Technical stack
Python, Spark, GCP (Compute Engine), Hadoop (HDFS, Hive, YARN), PostgreSQL.

## Project architecture


![Votre texte de paragraphe](https://github.com/benotsmane/US_healthcare_data_pipeline/assets/48206540/42b4d120-454c-4d5c-9b25-c5220f1283a4)


## Technical specification
We expect as a result, cities table and prescriber table with the below transformation

![image](https://github.com/benotsmane/US_healthcare_data_pipeline/assets/48206540/f78b7082-869b-431f-b5cf-e3a2d45b4f35)

![image](https://github.com/benotsmane/US_healthcare_data_pipeline/assets/48206540/98bc8aed-dc3b-462f-8e6d-18d072f9c70d)


- City Report:
  - Layout:
      - City Name
      - State Name
      - County Name
      - City Population
      - Number of Zips
      - Prescriber Counts
      - Total Trx counts


- Prescriber Report:
  - Layout:
      - Prescriber ID
      - Prescriber Full Name
      - Prescriber State
      - Prescriber Country
      - Prescriber Years of Experience
      - Total TRX Count
      - Total Days Supply
      - Total Drug Cost


## Running project
```
./bin/run_prescPipeline_project.ksh
```
