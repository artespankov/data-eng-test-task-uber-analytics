### GCP Components

#### Cloud Storage

File storage, similar to AWS S3 & Azure Blob

#### Compute Engine

Cloud computing service providing VMs

#### Big Query

Cloud-based Data Warehouse - store, analyze, query large amount of data with SQL.
Auto-scale to process Terabyte/Petabyte of data in real time.

#### Looker

Data visualisation and reporting

### Mage

Open-source data pipeline tool for data transformation & integration.
Easier & more interactive than Apache Airflow.
Using code template (coded beforehand for you)

### Facts & Dimensions

Fact Table

- quantitative measurements / metrics for analysis
- contains FKs to dimensions tables
- columns have high cardinality & change frequently
- contains the data that is not useful for analysis itself but for tracking the metrics
- examples - daily revenue, monthly product returns

Dimension Table

- descriptive attributes of data
- contains PKs linked by Fact Table
- low cardinality and mostly static
- data can be used for filtering & grouping
- examples - customers, products, dates & their attributes