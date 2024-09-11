# Web Scraping

![Mars Data](https://github.com/SakinaJaffri/Web-Scraping-Challenge/assets/146900226/97b2267f-d110-4185-ba27-a7d36adaff14)

## Project Overview

This project focuses on web scraping to collect and analyze Mars data using Python libraries such as `splinter`, `BeautifulSoup`, and `Pandas`. The collected data is organized into a Pandas dataframe and visualized for analysis to answer key questions about Mars, including its weather patterns and atmospheric conditions.

## Methodology

### Part 1: Mars News Scraping (`mars_news.ipynb`)
- **Objective**: Scrape the latest Mars news data.
- **Tools**: Splinter and BeautifulSoup for scraping.
- **Process**: 
  - Use a browser object to visit the Mars news site.
  - Parse the HTML using BeautifulSoup.
  - Extract the latest news titles and descriptions.
  - Store the data in a dictionary and append it to a list for analysis.

### Part 2: Mars Weather Scraping (`mars_weather.ipynb`)
- **Objective**: Scrape Mars weather data.
- **Tools**: Splinter and BeautifulSoup.
- **Process**: 
  - Scrape Mars weather data, focusing on temperature and atmospheric pressure.
  - Organize the scraped data into lists and convert them into a Pandas dataframe.
  - Perform further analysis and visualizations.

## Data Analysis

The project performs an analysis of the Mars weather data using Pandas and generates visualizations for the following:

1. **Number of months on Mars**: Use aggregation functions to count Martian months.
2. **Martian days in the dataset**: Identify how many Martian days (sols) are covered in the dataset.
3. **Coldest and warmest months on Mars**: Identify and visualize the coldest and warmest months at Curiosity's location.
4. **Lowest and highest atmospheric pressure months**: Analyze and plot atmospheric pressure trends across Martian months.
5. **Estimate of Earth days in a Martian year**: Visually estimate the length of a Martian year by plotting daily minimum temperatures.

## Data Storage

- The scraped and analyzed data is saved as a CSV file in the `Output` folder for future use and reference.

## Technologies Used

- **Python**: Core language for scraping and analysis.
- **Splinter**: Browser automation for web scraping.
- **BeautifulSoup**: HTML parsing and data extraction.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Data visualization.

## How to Run

1. Clone the repository to your local machine.
2. Install the necessary dependencies listed in `requirements.txt`.
3. Run the Jupyter notebooks (`mars_news.ipynb` and `mars_weather.ipynb`) to scrape the data and analyze it.

## Conclusion

This challenge demonstrates how to use web scraping to gather and analyze data from online sources, in this case, focusing on Mars news and weather patterns. The results offer insights into the Martian environment based on real-world data.

## Contributors

- **Sakina Jaffri** - Project Developer.
