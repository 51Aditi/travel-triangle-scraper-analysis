# Travel Triangle Web Scraping Data Analysis

A data analysis project that scrapes travel package information from TravelTriangle and turns it into actionable insights using Python. The project focuses on package pricing, destinations, durations, discounts, and package categories in the travel and tourism domain. 

## Project overview

This project was built to analyze travel packages and extract useful insights from a travel website dataset. The source website is TravelTriangle, the collection method is web scraping with Python, and the data is stored in CSV format for analysis. 

The notebook uses Python libraries including pandas, NumPy, seaborn, and matplotlib for data cleaning, exploration, and visualization. The scraping workflow is described as being done with BeautifulSoup. 

## Objectives

- Collect travel package data from TravelTriangle.
- Clean and transform the raw scraped dataset into analysis-ready data.
- Explore patterns in package prices, discounts, destinations, trip durations, and package types. 
- Generate visual insights for tourism and travel package trends. 

## Dataset details

The dataset contains 1,153 entries and 8 columns in its initial inspected form. The notebook shows the following fields in the dataset: `Name`, `Discount`, `DiscountPrice`, `original_Price`, `Days`, `Nights`, `Destination`, and `Package Type`. 

Example package categories visible in the dataset include `Honeymoon`, `Romantic`, `General`, and `Family`. Example destinations shown in the notebook include Goa, Andaman, Mussoorie, Coorg, Kerala, and Meghalaya. 

## Tech stack

- Python 
- BeautifulSoup 
- pandas 
- NumPy 
- seaborn 
- matplotlib 
- Jupyter Notebook 

## Workflow

### 1. Data collection
Travel package data was collected from the TravelTriangle website through web scraping. The scraped output was stored in CSV format for further analysis. 

### 2. Data cleaning
The notebook converts pricing and discount-related fields into numeric types. It also includes checks for null values and duplicate records before analysis. 

### 3. Exploratory data analysis
The project explores several useful dimensions of the dataset, including:

- Destination-wise package distribution.
- Package type distribution. 
- Discounted vs original price analysis. 
- Trip duration analysis using `Days` and `Nights`. 
- Duplicate detection and dataset quality checks. 

## Key observations

The dataset inspection in the notebook reports no null values across the listed columns at that stage of analysis. 

The notebook also identifies duplicate entries when checking package names, showing that data quality review is part of the workflow. 

Because the data includes original price, discounted price, trip days, nights, destination, and package type, it supports business-style analysis for travel trends and package comparison. 

## Project structure

```text
Travel-Triangle-Web-Scraping-Data-Analysis/
│
├── travel_triangle-csv.ipynb
├── webscrapping-Travel_triangle.ipynb
├── web-Scrapping-ppt-Aditi.pptx
├── fulldatasetupdated.csv
└── README.md
```

## Sample use cases

This project can be useful for:

- Travel package market analysis. 
- Tourism trend exploration. 
- Learning web scraping and data cleaning with Python. 
- Building a data analytics portfolio project. 

## How to run

1. Clone the repository.
2. Install required Python libraries.
3. Place the dataset CSV file in the correct project folder.
4. Open the notebook in Jupyter Notebook or JupyterLab.
5. Run the cells step by step to reproduce the analysis and charts.

Example installation:

```bash
pip install pandas numpy matplotlib seaborn beautifulsoup4 jupyter
```

## Future improvements

- Add more destinations and package records through expanded scraping.
- Build interactive dashboards for travel package comparison.
- Automate the scraping and cleaning pipeline.
- Add advanced visualizations and summary reports.

## Author

**Aditi Patil**  
BTech Final Year Student  
Interested in Python, web scraping, data analysis, and project deployment.

