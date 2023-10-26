# Yellow Taxi Trips Data Analytics | Data Engineering Azure Project

## Introduction
The "Yellow Taxi Trips Data Analytics" project uses modern technology and data analysis to extract valuable insights from New York City's yellow taxi trip records. I'm employing a range of advanced tools like Python, SQL, Azure services, and Power BI to process, analyze, and visualize the data.

## Architecture
<img src="https://media.licdn.com/dms/image/D5622AQEbpsxZAXyp7g/feedshare-shrink_800/0/1695830121501?e=1701302400&v=beta&t=Jo1JSQDtornIIDJgbUdxIcmsrw7FYtVFNa32ZdeLb70">

## Technologies Used
1. Python
2. SQL
3. Azure Data Factory
4. Azure Data Bricks
5. Azure Synapse Analytics
6. Power BI

## Dataset Used
1. Source : https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary : https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

The data is separated by months for each year, so I created a simple Python script to download all the Parquet files and combine them by year. The dataset is stored in .parquet.gzip format to be cost-effective for storage.

## Data Model
<img src="https://raw.githubusercontent.com/darshilparmar/uber-etl-pipeline-data-engineering-project/main/data_model.jpeg">

## Insights