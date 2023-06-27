
# End-to-End Sports Data Analytics Project: T20 World Cup Cricket Analysis

This repository contains an end-to-end sports data analytics project that focuses on analyzing T20 World Cup cricket data. The project encompasses web scraping, data processing using Python and pandas, and visualizations using Power BI.

# Project Credit

This project is based on the tutorial by [codebasics](https://www.youtube.com/watch?v=4QkYy1wANXA&t=4898s&ab_channel=codebasics). All credit for the project goes to codebasics.

## Project Overview

The objective of this project is to extract T20 World Cup cricket data from the ESPN Cricinfo website, perform data analysis, and create interactive visualizations to gain insights into the tournament. The project utilizes a combination of web scraping techniques, data manipulation, and powerful visualization tools to provide a comprehensive analysis of the T20 World Cup matches.

## Key Features

- **Web scraping:** The project includes a Python script that leverages the BeautifulSoup library to scrape T20 World Cup cricket data from the ESPN Cricinfo website. The script extracts information such as match details, player statistics, team performance, and other relevant data.
- **Data processing:** The extracted data is processed and cleaned using the pandas library in Python. This includes handling missing values, converting data types, and performing necessary transformations to prepare the data for analysis.
- **Analysis and insights:** Various statistical and exploratory analyses are conducted on the T20 World Cup cricket data. This includes analyzing player performance, team statistics, match outcomes, and trends over different tournament editions.
- **Interactive visualizations:** Power BI is used to create dynamic and visually appealing dashboards and reports. The visualizations enable users to interactively explore the data, discover patterns, and gain insights into the T20 World Cup matches. The dashboards provide a comprehensive overview of player performance, team dynamics, batting and bowling statistics, and other key aspects of the tournament.

## Repository Contents

- `web_scraping.py`: Python script for web scraping T20 World Cup cricket data from ESPN Cricinfo using BeautifulSoup.
- `data_processing.ipynb`: Jupyter Notebook demonstrating the data processing steps using pandas to clean and transform the extracted data.
- `analysis.ipynb`: Jupyter Notebook showcasing the data analysis and insights derived from the T20 World Cup cricket data.
- `power_bi_visualizations.pbix`: Power BI file containing interactive dashboards and reports with visualizations of the T20 World Cup cricket data.
- `data/`: Directory containing the extracted T20 World Cup cricket data in CSV format.

## Dependencies

- Python 
- Beautiful Soup
- Pandas
- Power BI

## How to Use

1. Clone the repository to your local machine.
2. Run `web_scraping.py` to scrape T20 World Cup cricket data from ESPN Cricinfo and save it in the `data/` directory.
3. Open the Jupyter Notebooks (`data_processing.ipynb` and `analysis.ipynb`) to explore the data processing steps and perform analysis on the extracted data.
4. Open `power_bi_visualizations.pbix` in Power BI to interact with the pre-built dashboards and reports.
