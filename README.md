# 🚀 Automated ETL Pipeline

## 📌 Project Overview

This project is an Automated ETL (Extract, Transform, Load) Pipeline designed to scrape fashion product data, clean and process it, and store it in a structured format for further analysis or machine learning use.

The pipeline automates the entire data workflow from extraction to final dataset generation.

## 🎯 Objectives
- Automate fashion product data collection through web scraping
- Clean and standardize raw scraped data
- Store processed data in a structured CSV format
- Provide a reusable ETL workflow for data analysis or ML tasks

# 🛠️ Tech Stack
- Python
- Pandas
- Requests / BeautifulSoup 
- Logging
- CSV handling

## Project Structure

```
Project_Automated-ETL-Pipeline/
│
├── tests/                     # Unit testing scripts
├── utils/                     # ETL helper functions and utilities
├── main.py                   # Main ETL pipeline script
├── products.csv              # Final output dataset
├── fashion_scraper_etl.log   # Pipeline execution logs
├── requirements.txt          # Project dependencies
├── submission.txt            # Notes / submission file
└── README.md
```

## ⚙️ ETL Workflow
1. Extract
Data is collected from fashion product websites using web scraping techniques.

2. Transform
The raw data is processed and cleaned by:
- Handling missing values
- Standardizing formats
- Removing invalid or duplicate entries
  
3. Load
The cleaned data is stored into:
- products.csv
     
## ▶️ How to Run the Project

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the pipeline
   ```bash
   python main.py
   ```

## 📊 Output
After running the pipeline, the processed dataset will be available at:
- products.csv

Execution logs are stored in:
- fashion_scraper_etl.log

## 🚀 Future Improvements

1. Add scheduling support (Cron / Apache Airflow)
2. Integrate with databases (MySQL / PostgreSQL)
3. Improve scraping performance and scalability
4. Build a dashboard for data visualization
