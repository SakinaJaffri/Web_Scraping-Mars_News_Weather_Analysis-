# Web-Scraping-Challenge


## Mars Data Analysis

## Overview

This challenge focuses on web scraping to retrieve data for analysis and informed decision-making. The process involves using Python libraries such as splinter and BeautifulSoup to scrape data from webpages, storing it in a Pandas dataframe, and visualizing it for analysis.

## Methodology

- **Part 1 (mars_news.ipynb)**: Scraping Mars news involves importing dependencies, creating a Browser object, and parsing HTML using BeautifulSoup. Extracted data is filtered and stored in a dictionary, then appended to a list for further analysis.

- **Part 2 (mars_weather.ipynb)**: Similar to Part 1, scraping Mars weather data involves parsing HTML and extracting relevant information. Data is organized into lists and converted into a Pandas dataframe for analysis.

## Analysis

The analysis includes answering questions using Pandas aggregate functions and plotting data for visual understanding:

1. How many months exist on Mars?
2. How many Martian (not Earth) days worth of data are in the dataset?
3. What are the coldest and warmest months on Mars (Curiosity's location)? Results are plotted as bar charts.
4. Which months have the lowest and highest atmospheric pressure on Mars? Results are plotted as bar charts.
5. How many Earth days are in a Martian year? Results are estimated visually by plotting daily minimum temperature.

## Data Storage

Retrieved data is stored as a CSV file in the Output folder for future reference.

