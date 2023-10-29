# Yellow Taxi Trips Data Analytics | Data Engineering Azure Project

<p align="center">
  <a href="https://github.com/aimanamri/yellow-taxi-trips-etl-data-engineering-project">
    <img alt="GitHub Language Count" src="https://img.shields.io/github/languages/count/aimanamri/yellow-taxi-trips-etl-data-engineering-project">
  </a>

  <a href="https://github.com/aimanamri/yellow-taxi-trips-etl-data-engineering-project">
    <img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/aimanamri/yellow-taxi-trips-etl-data-engineering-project">
  </a>
  
  <a href="https://github.com/aimanamri/yellow-taxi-trips-etl-data-engineering-project/stargazers">
    <img alt="GitHub Stars" src="https://img.shields.io/github/stars/aimanamri/yellow-taxi-trips-etl-data-engineering-project?style=social">
  </a>

  <a href="https://github.com/aimanamri/yellow-taxi-trips-etl-data-engineering-project/commits/main">
    <img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/aimanamri/yellow-taxi-trips-etl-data-engineering-project">
  </a>

  <a href="https://github.com/aimanamri/yellow-taxi-trips-etl-data-engineering-project">
    <img alt="Repository Size" src="https://img.shields.io/github/repo-size/aimanamri/yellow-taxi-trips-etl-data-engineering-project">
  </a>
</p>

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

The data is separated by months for each year, so I created a simple Python script to download all the Parquet files and combine them by year. The dataset is stored in .parquet.gzip format to be cost-effective for storage. But since it were too large to be stored on GitHub (without Git LFS), reducing the file size and using CSV format is the best solution by filtering the rows for this side project use. Here, first `20,000` rows randomly selected from each month will be used.

## Data Model
<img src="https://raw.githubusercontent.com/darshilparmar/uber-etl-pipeline-data-engineering-project/main/data_model.jpeg">

## Insights
