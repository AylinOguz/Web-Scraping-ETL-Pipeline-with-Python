# Web-Scraping-ETL-Pipeline-with-Python
![image]([https://github.com/AylinOguz/CLTV_Project/blob/main/Images/cltv.png?raw=true](https://github.com/AylinOguz/Web-Scraping-ETL-Pipeline-with-Python/blob/main/web_scraping.png?raw=true))

## Project Overview

This project demonstrates a simple ETL (Extract, Transform, Load) pipeline built with Python.
It scrapes data from a public website, cleans and transforms the data, then saves it into a CSV file and an SQLite database.
It also includes a logging system to track each step of the pipeline.


## How It Works

- Extract – The script sends HTTP requests to a website and scrapes data (like product names, prices, or ratings).

- Transform – The raw data is cleaned and formatted (e.g., removing symbols, converting data types).

- Load – The transformed data is saved into:

    - **A CSV file: transformed_data.csv**

    - **An SQLite database: etl_database.db**

- Log – All process steps are written to log_file.txt for debugging and traceability.
