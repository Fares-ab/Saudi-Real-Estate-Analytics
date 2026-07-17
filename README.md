# Saudi Real Estate Market Analytics Dashboard

## Project Overview

An end-to-end data analytics project that analyzes Saudi Arabia real estate listings to identify market trends, pricing patterns, location differences, and property distribution.

The project demonstrates a complete analytics workflow:

**Data Cleaning → SQL Analysis → Power BI Dashboard → Business Insights**

---

## Tools & Technologies

- Python
- Pandas
- MySQL
- SQL
- Power BI
- CSV

---

## Project Workflow

### 1. Data Cleaning & Preparation

The raw real estate dataset was explored, cleaned, and prepared using Python and Pandas.

Main tasks included:

- Reviewing the dataset structure
- Checking missing values
- Standardizing data types
- Cleaning inconsistent values
- Creating analytical columns
- Preparing the final dataset for MySQL and Power BI

Created features included:

- Price per Square Meter
- Listing Year
- Listing Month
- Period Month

The final dataset contains approximately **45,890 listings** and **22 columns**.

---

### 2. SQL Analysis

The cleaned dataset was imported into MySQL for analytical querying.

The SQL analysis included:

- Overall market KPIs
- Listings by city
- Average price by city
- Property category distribution
- Sale and rent distribution
- Listings growth by year
- District-level analysis
- Price per square meter analysis
- Area-band analysis

The SQL queries used in the project are available in:

```text
SQL/analysis_queries.sql
```

---

## Power BI Dashboard

The Power BI dashboard contains three interactive analytical pages.

Features include:

- Page navigation
- Interactive slicers
- Reset filter buttons
- Report-page tooltips
- Dynamic KPI values
- Key market insights
- Last refresh date
- Hidden tooltip pages
- Key Influencers visual

---

## Dashboard Pages

### Overview

The Overview page provides a high-level summary of the real estate market.

It includes:

- Total Listings
- Average Price
- Average Price per Square Meter
- Average Area
- Top Cities by Listings
- Property Category Distribution
- Listings Growth by Year
- Property Price Distribution
- Top Cities by Average Price

![Overview Dashboard](Images/Overview.png)

---

### City Analysis

The City Analysis page focuses on geographical and district-level patterns.

It includes:

- Property Locations Map
- Top Districts by Listings
- District Median Price per Square Meter
- Median Price by Area Band
- City Filter
- Interactive Tooltips

![City Analysis Dashboard](Images/City_Analysis.png)

---

### Property Analysis

The Property Analysis page focuses on property characteristics and pricing factors.

It includes:

- Listing Breakdown Analysis
- Key Drivers of Price per Square Meter
- Median Price by Property Category
- Listings and Median Price per Square Meter by Property Age
- Property Category Filter
- Key Influencers Analysis

![Property Analysis Dashboard](Images/Property_Analysis.png)

---

## Key Insights

- Riyadh has the highest number of real estate listings in the dataset.
- Land is the most listed property type.
- Sale listings represent the majority of the market.
- Property prices vary considerably by city, district, property type, and property size.
- Property characteristics and location strongly influence price per square meter.
- Listing activity increased significantly during the later years of the dataset.

---

## Project Structure

```text
Saudi-Real-Estate-Analytics/
│
├── Data/
│   └── cleaned_real_estate_listings.csv
│
├── Notebook/
│   └── data_cleaning.ipynb
│
├── SQL/
│   └── analysis_queries.sql
│
├── Dashboard/
│   └── Saudi_Real_Estate_Analytics.pbix
│
├── Images/
│   ├── Overview.png
│   ├── City_Analysis.png
│   └── Property_Analysis.png
│
└── README.md
```

---

## How to Use This Project

1. Open the notebook inside the `Notebook` folder.
2. Run all cells to review the data-cleaning process.
3. Review the SQL queries inside the `SQL` folder.
4. Open the Power BI file inside the `Dashboard` folder.
5. Use the page navigation, slicers, reset buttons, and tooltips to explore the dashboard.

---

## Author

Fares Abdullah Alghamdi

Computer Science Graduate  
Data Analytics & Business Intelligence