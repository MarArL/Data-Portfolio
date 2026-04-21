# Labor Market Data Analysis

## Project Overview

This project analyzes historical employment data in the United States using data from the Bureau of Labor Statistics.  
The goal is to identify long-term labor market trends, sector growth, and employment volatility across industries.

The project demonstrates a full data analysis workflow including:

- Data cleaning
- Data integration from multiple tables
- Exploratory data analysis
- Time series analysis
- Data visualization
- Business intelligence dashboard development

Tools used:

- Python
- Pandas
- Matplotlib
- Power BI

---

## Dataset

Source: U.S. Bureau of Labor Statistics (BLS)

Files used include:

- employment data
- industry classifications
- series metadata

The dataset contains more than **15 million observations** covering employment statistics from **1939 to 2017**.

You can download it here:

https://www.kaggle.com/datasets/bls/employment

---

## Data Processing

The analysis pipeline included:

- Filtering employment data (`data_type_code = 1`)
- Removing annual averages (`M13`)
- Creating time features
- Merging industry metadata
- Aggregating employment statistics

Final analytical dataset: **~1.6 million records**

---

## Key Analyses

### Employment over Time

Analysis of long-term employment trends across the U.S. economy.

### Top Industries by Employment

Identification of industries with the largest employment levels.

### Industry Employment Growth

Measurement of employment growth across industries.

### Industry Volatility

Standard deviation analysis to determine industries with the most volatile employment patterns.

---

## Visualizations

Key visual outputs include:

- Employment trends over time
- Top industries by employment
- Employment growth by industry
- Industry employment volatility

---

## Dashboard

An interactive dashboard was built using **Power BI** to explore employment data by industry and time.

Features include:

- Industry filters
- Time series analysis
- Top industry comparisons

---

## Repository Structure
labor-market-analysis
│
├── data
│ └── employment_dashboard_data.csv
│
├── images
│ ├── top_industries_employment.png
│ ├── employment_over_time.png
│ ├── industry_employment_growth.png
│ └── industry_volatility.png
│
├── notebooks
│ └── labor_market_analysis.ipynb
│
└── dashboard
└── labor_market_analysis.pbix

---

## Skills Demonstrated

- Data cleaning
- Data wrangling
- Data visualization
- Time series analysis
- Business intelligence dashboarding
- Large dataset processing

---

## Author

Marco Rojas